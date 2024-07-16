# print reciprocal letters

Problem link: [Click here](https://www.geeksforgeeks.org/problems/program-to-print-reciprocal-of-letters36233623/1?page=6&difficulty=School&sortBy=submissions)

```cpp
class Solution
{
public:
    string reciprocalString(string S)
    {
        int i = 0; 
        string str = "";
        while(i < S.length())
        {
            if(S[i] >= 'a' && S[i] <= 'z')
            {
                str+= 'z' - S[i] + 'a';
            }
            else if(S[i] >= 'A' && S[i] <= 'Z')
            {
                str+= 'Z' - S[i] + 'A';
            }
            else
            {
                str += S[i];
            }
            i++;
        }
        
        return str;
    }
};
```