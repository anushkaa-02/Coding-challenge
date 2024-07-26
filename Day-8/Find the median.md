# Find the median

Problem link: [Click here](https://www.geeksforgeeks.org/problems/find-the-median0527/1?page=1&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
	public:
		int find_median(vector<int>v)
		{
		    // Code here.
		    if((v.size())%2==0)
           {
               sort(v.begin(),v.end());
            int c= v.size()/2;
            int d=c-1;
            int g = (v[c]+v[d])/2;
            return g;
           }
            else
            {
                sort(v.begin(),v.end());
             double n = v.size()/2;
             int a =n;
             if(n>a)
             {
                n=n+0.5;
             }
            
             else
             {
                 n=a;
             }
             int b =v[n];
             return b;
            }
		    
		}
};
```
