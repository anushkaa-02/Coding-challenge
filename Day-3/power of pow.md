# Power of pow | odd number

Problem link : [Click here](https://www.geeksforgeeks.org/problems/power-of-pow-odd-numbers1103/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		long long int sum_of_square_oddNumbers(long long int n)
		{
		    // Code here.
		     long long int sum=0,i,num=1;
            for( i=1;i<=n;i++){
                sum=sum+num*num;
                num+=2;
            }
            return sum;
		}
};
```
