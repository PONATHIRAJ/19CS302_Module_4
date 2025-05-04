# EX 19  C PROGRAM TO FIND THE FREQUENCY OF THE CHARACTER. 
## DATE:04/05/2025
## AIM:
To write a program to find the frequency of the character. 

## Algorithm
1. Start. 
2. Define the required variable. 
3. Write program to find frequency of a character. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End. 

## Program:
```
#include<stdio.h> 
#include<string.h> 
int main() 
{ 
int i,count=0,len; 
char str[100],val[100];  
scanf("%s %s",str,val);  
len=strlen(str);  
for(i=0;i<len;i++){ 
if(str[i]==val[0])  
count++; 
}printf("%d",count);}
```

## Output:
![image](https://github.com/user-attachments/assets/f2b40f69-c2b9-487f-8983-c09d706d1535)

## Result:
Thus the program was executed and the output was verified successfully.
