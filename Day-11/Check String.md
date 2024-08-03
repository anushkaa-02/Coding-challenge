# Check String

Problem link: [Click here](https://www.geeksforgeeks.org/problems/check-string1818/1?page=3&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
    public:
        bool check (string s)
        {
        	//code here.
        	 for(int i=0; i<s.length()-1; i++){
                if(s[i]!=s[i+1]){
                    return false;
                }
            }
            return true;
        }
};
```