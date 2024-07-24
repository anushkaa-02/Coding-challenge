# Floyd's triangle

Problem Link : [Click here](https://www.geeksforgeeks.org/problems/floyds-triangle1222/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    void printFloydTriangle(int N)
    {
        // Write Your Code here
         int count=1;
        for(int i=0;i<N;i++){
            for(int j=0;j<=i;j++){
                cout<<count<<" ";
                count++;
            }
            cout<<endl;
        }
    }
};
```
