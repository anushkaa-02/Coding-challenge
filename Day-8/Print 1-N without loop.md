# Print 1-N without using loop

Problem link: [Click here](https://www.geeksforgeeks.org/problems/print-1-to-n-without-using-loops-1587115620/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution{
    public:
    //Complete this function
    void printNos(int N)
    {
        //Your code here
        if(N==0)return;
        printNos(N-1);
        cout<< N << " ";
    }
};
```
