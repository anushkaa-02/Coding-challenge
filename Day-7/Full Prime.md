# Full Prime

Problem link: [Click here](https://www.geeksforgeeks.org/problems/full-prime2659/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution{
    public:
	int fullPrime(int N){
	    //code here
	     if (N == 1) {
        return 0;
    }
    for (int i = 2; i * i <= N; i++) {
        if (N % i == 0) {
            return 0; 
        }
    }
    while (N > 0) {
        int r = N % 10;
        if (r == 0 || r == 1 || r == 4 || r == 6 || r == 8 || r == 9) {
            return 0; 
        }
        N /= 10;
    }
    return 1;
	}
};
```
