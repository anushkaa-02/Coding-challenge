# 12 hour clock subtraction

Problem link: [Click here](https://www.geeksforgeeks.org/problems/12-hour-clock-subtraction1708/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int subClock(int num1, int num2) {
        // code here
        int sub=(num1-num2)%12;
        if(sub>=0)
            return sub;
        else
            return 12+sub;
    }
};
```
