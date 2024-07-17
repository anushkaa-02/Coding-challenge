# Number of diagonals

Problem link: [Click here](https://www.geeksforgeeks.org/problems/number-of-diagonals1020/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution{
	public:
	long long diagonals(int n)
	{
		// Your code goes here
		long long ans=(long long)n;
		return (ans-1)*ans/2-ans;
        
	}
};
```

