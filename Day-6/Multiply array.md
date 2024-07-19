# Multiply array

Problem link: [Click here](https://www.geeksforgeeks.org/problems/multiply-array-1658312632/1?page=4&difficulty=School&sortBy=submissions)
```cpp
class Solution{
    public:
    int product(int arr[], int n)
    {
        int mul=1;
        for(int i=0;i<n;i++){
            mul*=arr[i];
        }
        return mul;
    }
};
```
