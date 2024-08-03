# Find difference between sum of diagonals

Problem link : [Click here](https://www.geeksforgeeks.org/problems/find-difference-between-sum-of-diagonals1554/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int diagonalSumDifference(int N, vector<vector<int>> Grid){
        // code here
         int s1=0,s2=0;
        int n = Grid.size();
        for(int i=0;i<n;i++)
        {
            s1+=Grid[i][i];
            s2+=Grid[i][n-1-i];
        }
        if(s1<s2)
            return  s2-s1;
        return s1-s2;
    }
};
```
