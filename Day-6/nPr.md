# nPr

Problem link: [Click here](https://www.geeksforgeeks.org/problems/npr4253/1?page=3&difficulty=School&sortBy=submissions)

```cpp
class Solution{
public:
    long long nPr(int n, int r){
        // code here
        long long result =1;
        while(r>0)
        {
            result*=n;
            n--;
            r--;
        }
        return result;
    }
};
```
