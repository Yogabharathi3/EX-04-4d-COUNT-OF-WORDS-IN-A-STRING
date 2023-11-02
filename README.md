# EX-04-4d-COUNT-OF-WORDS-IN-A-STRING
## AIM 
Write a C Program to count the total number of words in a given string using do While loop. 
## ALGORITHM 
1. Start the program. 
2. Read a string variable. 
3. Using for loop, inspect the string character by character. 
4. Whenever a space is encountered increment count by 1. 
5. Display the result. 
6. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
#include<string.h> 
int main() 
{ 
 char s[50]; 
 scanf("%[^\n]",s); 
 int flag=1; 
 for( int i=0;i<strlen(s);i++) 
 { 
 if(s[i]== ' ') 
 flag++; 
 } 
 printf("%d",flag); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-04-4d-COUNT-OF-WORDS-IN-A-STRING/assets/118899387/e84985ff-1bac-4f28-bb13-ceade5c468bf)
## RESULT 
Thus the program to count the total number of words in a given string using do 
While loop has been executed successfully
