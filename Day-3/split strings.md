# Split strings

Problem link: [Click here](https://www.geeksforgeeks.org/problems/split-strings5211/1?page=5&difficulty=School&sortBy=submissions)

```cpp
class Solution
{   
public:
    vector<string> splitString(string S) 
    { 
        // code here 
        vector<string>s;
        string s1,s2,s3;
        for(int i=0;i<S.length();i++){
            if((S[i]>='A' && S[i]<='Z') || (S[i]>='a' && S[i]<='z'))
                s1.push_back(S[i]);
            else if(S[i]<='9' && S[i]>='0')
                s2.push_back(S[i]);
            else
                s3.push_back(S[i]);
        }
        s.push_back(s1);
        s.push_back(s2);
        s.push_back(s3);
        return s;
    } 
};
```
