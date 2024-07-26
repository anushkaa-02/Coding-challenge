# Sum of Array

Problem link: [Click here](https://www.geeksforgeeks.org/problems/sum-of-array2326/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    // Function to return sum of elements
    int sum(vector<int>& arr) {
        // code here
        int sum = 0;
        for (int i = 0; i < arr.size(); i++) sum += arr[i];
        return sum;
    }
};
```
