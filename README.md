
# EX-01-Datatypes-Operators
## AIM:
Write a C program to initialize the character as z & display the same character.
## ALGORITHM:
Start the program.

Declare a character variable and initialize it to 'z'.

Display the character using printf().

End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
char a ='z';
printf("%c",a);
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e9f2f4e2-2c4d-422a-adf1-2883c9e442d8)


## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C Program to print numbers(10 to 14) into words using the switch statement (EX. 10 -TEN, 13-THIRTEEN)

# ALGORITHM:
Start the program and declare an integer variable.

Read or assign a number between 10 and 14.

Use a switch statement to match and print the word for that number.

End the program.
# PROGRAM:
```
#include<stdio.h>
int main(){
    int num;
    scanf("%d",&num);
        switch(num){
            case 10:printf("TEN\n");break;
            case 11:printf("ELEVEN\n");break;
            case 12:printf("TWELVE\n");break;
            case 13:printf("THIRTEEN\n");break;
            case 14:printf("FOURTEEN\n");break;
            default:printf("... Plz Enter 10 to 14 Numbers Only...");
            
            
        }
    }
```

# OUTPUT:

![image](https://github.com/user-attachments/assets/a4c1d478-35e4-4239-8a48-fd8edf546f5f)

# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 
# EX-03- Operators-Expressions
## AIM:
Debug the given C program to find the number of years based on principle amount, rate of interest & simple interest.

## ALGORITHM:
Start the program and declare variables for principal (P), rate (R), interest (SI), and time (T).

Input values for principal, rate, and simple interest.

Use the formula T = SI / (P * R / 100) to calculate the number of years.

Display the result and end the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float principle, year, rate, SI;
      scanf("%f", &principle);
      scanf("%f", &rate);
      scanf("%f", &SI);
      year= SI / (principle * rate/100);
      printf("No.of.Year is = %.2f", year);
      return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/2798d571-62c8-449a-826d-624d2965bd01)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to count the number of digits without using a loop

## ALGORITHM:
Start the program and define a recursive function to count digits.

In the function, check if the number is 0; if so, return 0.

Otherwise, return 1 + recursive call with number / 10.

Call the function with the input number and print the result.

## PROGRAM:
```
#include <stdio.h>  
#include<math.h>  
int main()  
{  
    int num;  // variable declaration  
    int count=0;  // variable declaration  
     
   scanf("%d",&num);  
   count=(num==0)?1: log10(num)+1;  
   printf("Number:%d",count);  
   return 0;  
}  
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/d67f6bf0-4edc-4c65-b97d-bc1dd4dbcb23)

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C program to check whether the given number is  odd number and it is greater than 25 or not using nested if.
## ALGORITHM:
1.Start the program and input a number.

2.Check if the number is odd using if (num % 2 != 0).

3.Inside that, use another if to check if it is greater than 25.

4.Print appropriate messages based on conditions and end the program.


## PROGRAM:
```
#include <stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    
    if(a%2!=0){
        if(a>=25){
            printf("The number is odd");
            printf("\nThe number is greater than or equal to 25");
        }
        else{
            printf("The number is odd");
            printf("\nThe number is not greater than or equalto 25");
        }
    }
    else{
        printf("The number is NOT an odd number");
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/405e7b81-acdd-4722-8b23-5d95992ad551)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

