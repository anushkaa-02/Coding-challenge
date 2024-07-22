# Multiplication Table

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/print-table0303/1?page=2&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    vector<int> getTable(int N)
    {
        // Write Your Code here
        vector<int>ans;
        for(int i=1;i<=10;i++){
            int a=i*N;
            ans.push_back(a);
        }
        return ans;
    }
};
```
