# Even Odd Sum

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/even-odd-sum5450/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution {
  public:
    vector<int> EvenOddSum(int N, int Arr[]) {
        // code here
       int sumodd=0,sumeven=0;
       for(int i=0;i<N;i++){
           if(i%2==0){
               sumeven += Arr[i];
           }
           else{
               sumodd += Arr[i];
           }
       }
       return {sumeven,sumodd};
    }
};
```
