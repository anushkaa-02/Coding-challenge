# Sum of GP

Problem link: [Click here](https://www.geeksforgeeks.org/problems/sum-of-gp2120/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		long sum_of_gp(long n,long a, long r)
		{
		    // Code here
		     if (r==1)
            return n*a;
            return (a*(pow(r,n)-1)/(r-1));
		}
};
```
