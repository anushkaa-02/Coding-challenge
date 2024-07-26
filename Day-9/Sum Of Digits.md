# Sum Of Digits

Problem link: [Click here](https://www.geeksforgeeks.org/problems/sum-of-digits1742/1?page=2&difficulty=School&sortBy=submissions)

```cpp
class Solution{
public:
    int sumOfDigits(int N){
        //code here
        int sum = 0;
        while (N > 0) {
        sum += N % 10;
        N /= 10;
        }
        return sum;
    }
};
```
