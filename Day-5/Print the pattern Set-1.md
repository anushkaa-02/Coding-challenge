# Print the pattern | Set-1

Problem link: [Click here](https://www.geeksforgeeks.org/problems/print-the-pattern-set-1/1?page=1&difficulty=School&sortBy=submissions)

```cpp
void printPat(int n) {
    // Your code here
    int p = n ;
    while(p>0){
    int x = n;
    for(int i = 0; i < n ;i++){
        for(int j =0 ; j < p ; j++){
            cout <<x<<" ";
        }
        x--;
    }
    cout << "$";
    p--;
    }
}
```
