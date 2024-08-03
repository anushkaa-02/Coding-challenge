# Upper case conversion

Problem Link: [Click here](https://www.geeksforgeeks.org/problems/upper-case-conversion5419/1?page=2&difficulty=School&sortBy=submissions)

```cpp
string transform(string s)
{
    // code here
     s[0] = toupper(s[0]);
    for (int i = 0; i < s.size(); i++) {
            if (s[i] == ' ') {
                s[i+1] = toupper(s[i+1]);
            }
        }
        return s;
}
```