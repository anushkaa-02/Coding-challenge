# Sum palindrome

Problem link: [Click here](https://www.geeksforgeeks.org/problems/sum-palindrome3857/1?page=3&difficulty=School&sortBy=submissions)


```cpp

class Solution {
  public:
    long long isSumPalindrome(long long n){
        // code here
        int k = 6;
        while(k--){
            int rev = 0,m=n;
            while(m){
                int rem = m%10;
                rev = (rev*10)+rem;
                m /= 10;
            }
            if(rev == n){
                return n;
            }
            n = rev+n;
        }
        return -1;
    }
};
```
