# Pattern printing

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/pattern-printing1347/1?page=4&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    void printPattern(int N)
        {
        for(int i=1;i<=N;i++){
            cout<<string(i,'*')<<" ";
        }
    }
};
```
