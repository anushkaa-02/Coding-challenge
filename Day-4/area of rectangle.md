# Area of rectangle, Right Angled Triangle and Circle

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/area-of-rectange-right-angled-triangle-and-circle2600/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    vector<int> getAreas(int L ,int W ,int B ,int H ,int R) {
        // code here
        return{L*W ,(B*H)/2 ,3.14*R*R};
    }
};
```

