# Union of Two arrays

Problem link: [Click here](https://www.geeksforgeeks.org/problems/union-of-two-arrays3538/1?page=1&difficulty=Basic&sortBy=submissions)

```cpp
class Solution {
  public:
    // Function to return the count of number of elements in union of two arrays.
    int doUnion(vector<int> arr1, vector<int> arr2) {
        // code here
         set<int>s;
        for(int i =0;i<arr1.size();i++){
            s.insert(arr1[i]);
        }
        for(int i =0;i<arr2.size();i++){
            s.insert(arr2[i]);
        }
        return s.size();
    }
};
```
