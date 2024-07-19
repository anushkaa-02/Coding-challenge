# 12 hour clock Multiplication

Problem link: [Click here](https://www.geeksforgeeks.org/problems/12-hour-clock-multiplication4709/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int mulClock(int num1, int num2) {
        // code here
         int product = (num1*num2);
        if(product<12)
        return product;
        return product%12;
    }
};
```
