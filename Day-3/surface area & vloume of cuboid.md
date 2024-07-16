# surface area & vloume of cuboid

Problem link : [Click here](https://www.geeksforgeeks.org/problems/surface-area-and-volume-of-cuboid0522/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution{
	public:
	vector<long long int> find(int l, int b, int h)
	{
	    // Code here
	    long long int L=l , B=b , H=h;
	    return { 2*(L*B + B*H + H*L) , L*B*H };
	    
	}  
};
```
