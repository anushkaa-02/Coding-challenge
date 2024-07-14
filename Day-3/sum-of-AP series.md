# Sum of AP series
Problem link: [Click here](https://www.geeksforgeeks.org/problems/sum-of-ap-series4512/1?page=4&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		long sum_of_ap(long n,long a, long d)
		{
		    // Code here.
		  long t=(2*a+(n-1)*d);
      return long((n*t)/2);
		}
};
```
