# Automorphic Number

Problem link: [Click here](https://www.geeksforgeeks.org/problems/automorphic-number4721/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		string is_AutomorphicNumber(int n)
		{
		    // Code here
		    string s = (n*n)%10==n%10?"Automorphic":"Not Automorphic";
            return s;
		}
};
```
