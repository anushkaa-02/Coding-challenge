# Distance between two pointers

Problem link: [Click here](https://www.geeksforgeeks.org/problems/distance-between-2-points3200/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
	public:
		int distance(int x1, int y1, int x2, int y2)
		{
		    // Code here.
		    return (int) round(sqrt((x1-x2)*(x1-x2)+(y1-y2)*(y1-y2)));
		}
};
```
