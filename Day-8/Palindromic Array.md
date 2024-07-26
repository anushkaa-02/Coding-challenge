# Palindromic Array

Problem link: [Click here](https://www.geeksforgeeks.org/problems/palindromic-array-1587115620/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    bool PalinArray(vector<int> &arr){
        // code here
        for(int num:arr){
            int temp=num;
            int rev=0;
            while(temp){
                int digit=temp%10;
                rev=rev*10+digit;
                temp=temp/10;
            }
            if(rev!=num){
                return false;
                }
            }
        return true;
    }
};
```
