## EXPERIMENT-1-CHARACTER TO ASCII CONVERTER

### AIM:
To develop a C program to display the ASCII value of a given character.

### ALGORITHM:
1. Start the program execution.

2. Declare a variable `i` of type char to store the input character.

3. Prompt the user to input a character.

4. Read the character input using `scanf()` function and store it in the variable `i`.

5. Print the message "ASCII value of \<character\> is \<ASCII value\>" using `printf()` function, where \<character\> is the input character and \<ASCII value\> is its corresponding ASCII value obtained by printing `i` as an integer.

6. End the program.

## PROGRAM:
``` 

'''
Developed by:Ezhil sree J 
RegisterNumber: 212223230056
'''
#include<stdio.h>
int main()
{
    char i;
    scanf("%c",&i);
    printf("ASCII value of %c is %d",i,i);
}
        

```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/afbb8bcb-cd44-4024-8959-ff2248ba1857)

## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/d9148b49-24e5-4cdf-8e9e-3375c88eeeca)



## RESULT:
Thus the required program is written and executed successfully.

