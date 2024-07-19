# Check for binary

Problem link: [Click here](https://www.geeksforgeeks.org/problems/check-for-binary/1?page=1&difficulty=School&sortBy=submissions)
```cpp
bool isBinary(string str)
{
   // Your code here
   for(int i=0;i<str.length();i++){
       if(str[i]!='0'&&str[i]!='1'){
           return false;
       }
   }
   return true;
}
```
