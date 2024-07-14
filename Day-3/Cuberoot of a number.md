# Cuberoot of a number

Problem link: [Click here](https://www.geeksforgeeks.org/problems/cube-root-of-a-number0915/1?page=5&difficulty=School&sortBy=submissions)
```cpp
class Solution {
  public:
    int cubeRoot(int N) {
        // code here
        int start=0, end=N;
        if(N<=1) return N;
        int mid, ans;
        while(start<=end){
            mid=start+(end-start)/2;
            if((long long) mid*mid*mid<= N){
                ans=mid;
                start+=1;
            }
            else if((long long) mid*mid*mid<N){
                start=mid+1;
            }
            else{
                end=mid-1;
            }
        }
        return ans;
    }
};
```
