# Small Factorial

Problem link: [Click here](https://www.geeksforgeeks.org/problems/small-factorial0854/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		long long int find_fact(int n)
		{
		    // Code here.
		    long long int fact = 1;
            for (int i = 2; i <= n; i++) {
                fact *= i;
            }
            return fact;
		}
};
```
