# 1s Complement

Problem link: [Click here](https://www.geeksforgeeks.org/problems/1s-complement2819/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution{ 
public:
    string onesComplement(string S,int N){
        //code here
         string str = "";
        for(int i=0;i<N;i++){
            if(S.at(i)==49){
                str += "0";
            }
            else
                str += "1";
        }
        return str;
    }
};
```

