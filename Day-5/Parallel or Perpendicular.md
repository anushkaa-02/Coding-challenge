# Parallel or Perpendicular?

Problem link: [Click here](https://www.geeksforgeeks.org/problems/parallel-or-perpendicular4257/1?page=6&difficulty=School&sortBy=submissions)
```cpp
class Solution{
	public:
	int find(vector<int>A, vector<int>B){
	    //  Code here
	    int sumDot=0;
        for(int i=0;i<3;i++){
            sumDot+=(A[i]*B[i]);
        }
        if(sumDot==0)
            return(2);
    
        int cross1=(B[2]*A[1]-B[1]*A[2]);
        int cross2=(B[0]*A[2]-B[2]*A[0]);
        int cross3=(A[0]*B[1]-B[0]*A[1]);
        
        int cross=(cross1*cross1)+(cross2*cross2)+(cross3*cross3);
        if(cross==0)
        return(1);
        return(0);
	}
};
```
