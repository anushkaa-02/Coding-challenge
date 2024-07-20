# Palindrome

Problem link: [Click here](https://www.geeksforgeeks.org/problems/palindrome0746/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
	    string is_palindrome(int n)
		 int rev=0, copy=n;
            if(n<0) return "No";
            while(n>0){
                rev=rev*10+n%10;
                n/=10;
            }
            if(copy==rev){
                return "Yes";
            } else {
                return "No";
        }
    }
};
```
