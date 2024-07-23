# Sum of odd and even elements

Problem link: [Click here]()

```cpp
class Solution
{
	public:
		vector<int> find_sum(int n)
		{
		    // Code here
		     vector<int>arr;
            int odd=0;
            int even=0;
            for(int i=1;i<=n;i++){
                if(i%2)
                    odd+=i;
                else
                    even+=i;
            }
            arr.push_back(odd);
            arr.push_back(even);
            return arr;
		}
};
```
