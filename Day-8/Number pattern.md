# Number pattern

Problem link: [Click here](https://www.geeksforgeeks.org/problems/number-pattern0517/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    vector<string> numberPattern(int N)
    {
        // Write Your Code here
         vector<string>S;
        
        for(int i=1;i<=N;i++){
            string s="";
            int count=0;
            for(int j=1;j<=i;j++){
                count++;
                s=s+to_string(count);
            }
            for(int k=i;k>1;k--){
                count--;
                s=s+to_string(count);
            }
        S.push_back(s);
        }
        return S;
    }
};
```
