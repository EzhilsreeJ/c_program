## EXPERIMENT-1-FLOATING POINT NUMBER FORMATTER

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


## EXPERIMENT-3-GREATER INTEGER COMPARISON

### AIM:
To develop a program that compares two integer inputs and prints the greatest one.

### ALGORITHM:
1. Start the program.
2. Declare two variables `a` and `b` of type int to store the integer inputs.
3. Prompt the user to input two integers.
4. Read the integer inputs using `scanf()` function and store them in variables `a` and `b`.
5. Use an if-else statement to compare `a` and `b`.
6. If `a` is greater than `b`, print "A is greatest." using `printf()` function.
7. If `b` is greater than `a`, print "B is greatest." using `printf()` function.
8. End the program.

## PROGRAM:
``` 
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if (a>b)
    printf("A is greatest.");
    else
    printf("B is greatest.");
    
    
} 

```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/8d0a17eb-30bf-4bba-8c76-ae8bb378eb61)



## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/28c220b3-c4cf-4d12-986f-05d58ff04f70)




## RESULT:
Thus the required program is written and executed successfully.


## EXPERIMENT-4-INTEGER COMPARISON

### AIM:
To develop a program that compares two integer inputs and informs whether they are equal or not, and if not, which one is greater.

### ALGORITHM:
1. Begin the program.
2. Declare two variables `a` and `b` of type int to store the integer inputs.
3. Prompt the user to input two integers.
4. Read the integer inputs using `scanf()` function and store them in variables `a` and `b`.
5. Use an if-else statement to check if `a` is not equal to `b`.
   i) If `a` is not equal to `b`, execute the following steps:
      Print "A is not equal to B".
      Use nested if-else statements to determine which integer is larger:
        If `a` is greater than `b`, print "A is larger than B".
        If `b` is greater than `a`, print "B is larger than A".
   ii) If `a` is equal to `b`, print "A is equal to B".
6. End the program.

## PROGRAM:
``` 
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if(a!=b)
    {
        printf("A is not equal to B");
        if(a>b)
        printf("\nA is larger than B");
        else
        printf("\nB is larger than A");
    }

    else
    printf("A is equal to B");
}

```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/b8401cfa-3b0c-4c87-a1e2-0547794bf3c3)




## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/1c6246d1-866c-4eb7-bcff-bd9f2c536309)





## RESULT:
Thus the required program is written and executed successfully.


## EXPERIMENT-5-RATE OF INTEREST CALCULATOR

### AIM:
To create a program that calculates the rate of interest based on the principal amount, rate, and simple interest provided by the user.

### ALGORITHM:
1. Begin the program.
2. Declare variables `p` (principal), `r` (rate), `si` (simple interest), and `y` (rate of interest in percentage) of type float.
3. Prompt the user to input the principal amount, rate, and simple interest.
4. Read the input values for `p`, `r`, and `si` using `scanf()` function.
5. Calculate the rate of interest (`y`) using the formula: \[ y = \frac{si \times 100}{r \times p} \]
6. Print the rate of interest (`y`) with two decimal places using `printf()` function.
7. End the program.

## PROGRAM:
``` 
#include<stdio.h>
int main(){
    float p,r,si;
    scanf("%f%f%f",&p,&r,&si);
    float y;
    y=(si*100)/(r*p);
    printf("Rate of Interest is = %.2f percentage",y);
    
}
```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/d3e2e04c-c13f-4fd4-8986-cc816d15195d)



## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/c25055ce-c585-47cb-b55b-3fa73bbf550d)



## RESULT:
Thus the required program is written and executed successfully.



## EXPERIMENT-6-MINIMUM VALUE CALCULATOR

### AIM:
To develop a program that calculates the minimum value between two floating-point numbers provided by the user.

### ALGORITHM:
1. Begin the program.
2. Declare variables `a` and `b` of type float to store the input floating-point numbers.
3. Prompt the user to input two floating-point numbers separated by space.
4. Read the input values for `a` and `b` using `scanf()` function.
5. Use the ternary conditional operator `(a < b) ? ... : ...` to compare `a` and `b`:
   i) If `a` is less than `b`, print "Minimum between \<a\> and \<b\> is \<a\>" using `printf()` function with formatting specifier "%.3f" to display the minimum value `a` with three decimal places.
   ii) If `b` is less than `a`, print "Minimum between \<a\> and \<b\> is \<b\>" using `printf()` function with formatting specifier "%.3f" to display the minimum value `b` with three decimal places.
6. End the program.

## PROGRAM:
``` 
#include <stdio.h>
int main()
{
    float a,b;
    scanf("%f %f",&a,&b);
    (a < b) ? printf("Minimum between %.3f and %.3f is %.3f",a,b,a):printf("Minimum between %.3f and %.3f is %.3f",a,b,b);
}
```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/a6a0cbfe-c910-4364-9cad-4dd80103054d)



## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/6e1ad061-aea5-41da-93f2-dfa02193b37d)




## RESULT:
Thus the required program is written and executed successfully.


## EXPERIMENT-7-MAXIMUM NUMBER FINDER

### AIM:
 To create a program that identifies the maximum number among three integers provided by the user.

### ALGORITHM:
1 Begin the program.
2. Declare variables `r`, `p`, and `k` of type int to store the input integers.
3. Prompt the user to input three integers.
4. Read the input values for `r`, `p`, and `k` using `scanf()` function.
5. Use nested if-else statements to compare the three integers:
i) If `r` is greater than both `p` and `k`, print "Maximum Number is \<r\>" using `printf()` function.
ii) Else, if `p` is greater than both `r` and `k`, print "Maximum Number is \<p\>" using `printf()` function.
iii) Otherwise, print "Maximum Number is \<k\>" using `printf()` function.
6. End the program.

## PROGRAM:
``` 
#include <stdio.h>
int main()
{
    int r,p,k;
    scanf("%d%d%d",&r,&p,&k);
    if (r>p && r>k)
    printf("Maximum Number is %d",r);
    else if(p>r && p>k)
    printf("Maximum Number is %d",p);
    else
    printf("Maximum Number is %d",k);
 return 0;   
}
```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/1590ac35-ab40-4e6b-b29d-94ab7ce6c4bb)



## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/f61a34a0-859e-4b90-92f3-c5dbb06952e0)




## RESULT:
Thus the required program is written and executed successfully.


## EXPERIMENT-8-ELIGIBILITY FOR MARRIAGE**

 **AIM:**
    To determine if a person is eligible for marriage based on their age.

**ALGORITHM:**
   1. Begin the program.
   2. Declare a variable `age` of type int to store the age of the person.
   3. Prompt the user to input their age.
   4. Read the input value for `age` using `scanf()` function.
   5. Use an if statement to check if the `age` is greater than or equal to 18:
      - If true, print "She is eligible for marriage" using `printf()` function.
   6. End the program.
## PROGRAM:
``` 
#include <stdio.h>
int main()
{
    int age;
    scanf("%d",&age);
    if (age>=18)
    printf("she is eligible for marriage");
    
 return 0;   
}
```
## SAMPLE OUTPUT :

![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/66a1eb0e-e983-4f9f-807f-afd4acf3a01c)




## OUTPUT :
![image](https://github.com/EzhilsreeJ/c_program/assets/144870412/66a1eb0e-e983-4f9f-807f-afd4acf3a01c)





## RESULT:
Thus the required program is written and executed successfully.



















