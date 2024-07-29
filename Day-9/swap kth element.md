# Swap kth element

Problem link: [Click here](https://www.geeksforgeeks.org/problems/swap-kth-elements5500/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    void swapKth(int k, vector<int> &arr) {
        // code here
        for(int i=0;i<arr.size();i++){
            if(i==k-1){
                swap(arr[i],arr[arr.size()-k]);
            }
        }
    }
};
```
