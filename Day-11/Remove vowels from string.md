# Remove vowels from string

Problem link: [Click here](https://www.geeksforgeeks.org/problems/remove-vowels-from-string1446/1?page=2&difficulty=School&sortBy=submissions)

```cpp
class Solution{
public:	
	string removeVowels(string S) 
	{
	    // Your code goes here
	     string res;
        for(char c: S )
        {
            if(c=='A'||c=='E'||c=='I'||c=='O'||c=='U'||c=='a'||c=='e'||c=='i'||c=='o'||c=='u')
            {
                continue;
            }
            res+=c;
        }
        return res;
	}
};
```