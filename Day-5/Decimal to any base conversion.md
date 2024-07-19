# Decimal to any base conversion

Problem link: [Click here](https://www.geeksforgeeks.org/problems/decimal-to-any-base-conversion2440/1?page=7&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    string getNumber(int B, int N)
    {
        // Write Your Code here
        string result="";
        int digit;
        string temp;
        while(N>0){
            digit=N%B;
            temp=to_string(digit);
            switch (digit){
                case 10: temp="A";
                break;
                case 11: temp="B";
                break;
                case 12: temp="C";
                break;
                case 13: temp="D";
                break;
                case 14: temp="E";
                break;
                case 15: temp="F";
                break;
            }
            result=temp+result;
            N/=B;
        }
        return result;
    }
};
```
