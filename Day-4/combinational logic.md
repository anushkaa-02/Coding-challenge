# Combinational logic

Problem link: [Click here](https://www.geeksforgeeks.org/problems/combinational-logic1908/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int logicalOperation(int A,int B,int C,int D,int E,int F){
        // code here
        return ((!(A))&&B||C&&D||E&&(!(F)));
    }
};
```
