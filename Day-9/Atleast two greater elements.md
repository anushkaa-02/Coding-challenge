# Atleast two greater elements

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/at-least-two-greater-elements4625/1?page=2&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    vector<int> findElements(vector<int> arr){
        // Your code goes here
        sort(arr.begin(), arr.end());
        arr.pop_back();
        arr.pop_back();
        return arr;
    }
};
```
