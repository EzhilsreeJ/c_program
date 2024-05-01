## EXPERIMENT-2-FLOATING POINT NUMBER FORMATTER

### AIM:
To create a program that reads a floating-point number from the user and prints it with two decimal places.

### ALGORITHM:
1. Begin the program.
2. Declare a variable `a` of type float to store the input floating-point number.
3. Prompt the user to input a floating-point number.
4. Read the floating-point number input using `scanf()` function and store it in the variable `a`.
5. Print the value of `a` using `printf()` function with formatting specifier "%.2f" to display it with two decimal places.
6. End the program.

## PROGRAM:
``` 
#include <stdio.h>
int main()
{
    float a;
    scanf("%f",&a);
    printf("%.2f",a);
}    

```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/562bb800-3a05-4b27-a22a-bee3f9925915)


## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/90625d8a-e8ee-4195-bfb2-99680c8282e3)




## RESULT:
Thus the required program is written and executed successfully.

