# Peak element

Problem link: [Click here](https://www.geeksforgeeks.org/problems/peak-element/1?page=1&difficulty=Basic&sortBy=submissions)

```cpp
class Solution
{
    public:
    int peakElement(int arr[], int n)
    {
       // Your code here
       for(int i=n-1;i>0;i--){
           if(arr[i]>arr[i-1]) return i;
       }
    }
};
```
