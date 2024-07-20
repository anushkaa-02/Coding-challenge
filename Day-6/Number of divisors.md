# Number of divisors

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/number-of-divisors1631/1?page=4&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		int count_divisors(int n)
		{
		    int count =0;
            for(int i=1;i<=sqrt(n);i++)
            {
                if(n%i==0){
                    if(i%3==0 )
                        count++;
                     if(i!=n/i && (n/i)%3==0){
                         count++;
                    }
                }
                    
            }
           return count;
		}
};
```
