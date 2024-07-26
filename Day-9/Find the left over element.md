# Find the left over element

Problem link: [Click here](https://www.geeksforgeeks.org/problems/print-the-left-element2009/1?page=2&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int leftElement(vector<int> &arr) {
        // Your code goes here
        sort(arr.begin(),arr.end());
        int left = 0;
        int right = arr.size() - 1;
        
        bool removeFromEnd = true;
        while (left < right) {
            if (removeFromEnd) {
                --right;
            } else {
                ++left;
            }
            removeFromEnd = !removeFromEnd;
        }
        return arr[left];
    }
};
```
