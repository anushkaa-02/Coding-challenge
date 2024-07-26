# Alternates in an array

Problem link: [Click here](https://www.geeksforgeeks.org/problems/print-alternate-elements-of-an-array/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    // arr[] is the array
    void print(vector<int> &arr){
        // code here
         int i;
        for(i=0;i<arr.size();i++)
        {
            if(i%2==0)
            {
                cout<<arr[i]<<" ";
            }
        }
    }
};
```
