# Compound interest

Problem link: [Click here](https://www.geeksforgeeks.org/problems/compound-interest0235/1?page=6&difficulty=School&sortBy=submissions)

```cpp

class Solution {
  public:
    int getCompundInterest(int P,int T ,int N ,int R) {
        // code here
        int A;
        A=P*pow((1+((R/100.0)/N)),N*T);
        return A;
    }
};
```
