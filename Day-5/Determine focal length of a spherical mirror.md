# Determine focal length of a spherical mirror

Problem link: [Click here](https://www.geeksforgeeks.org/problems/determine-focal-length-of-a-spherical-mirror5415/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution{
	public:
	int findFocalLength(float R, string type){
	    //Code here
	     if(type=="convex")
            return floor(-R/2);
        else
            return floor(R/2);
	}
};
```
