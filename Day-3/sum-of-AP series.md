# Sum of AP series


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
