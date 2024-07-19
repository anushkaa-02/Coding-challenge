# Check if two given circles touch each other

Problem link: [Click here](https://www.geeksforgeeks.org/problems/checcheck-if-two-given-circles-touch-each-other5038/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    int circleTouch(int X1,int Y1,int R1,int X2,int Y2,int R2){
        // code here
        float c1c2= sqrt((X2-X1)*(X2-X1)+(Y2-X1)*(Y2-X1));
        if(c1c2<=R1+R2)
        return 1;
        return 0;
    }
};
```
