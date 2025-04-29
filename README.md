
# EX-01-Datatypes-Operators
## AIM:
Write a C program to initialize the character as z & display the same character.-----

## OUTPUT:

## ALGORITHM:
1.Start the program.

2.Declare a character variable and initialize it to 'z'.

3.Display the character using printf().

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
# OUTPUT:

![image](https://github.com/user-attachments/assets/994f6242-e071-4abe-abf1-03ee417fb8cd)



## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C Program to print numbers(10 to 14) into words using the switch statement (EX. 10 -TEN, 13-THIRTEEN)

# ALGORITHM:
1.Start the program and declare an integer variable.

2.Read or assign a number between 10 and 14.

3.Use a switch statement to match and print the word for that number.

4.End the program.

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

![image](https://github.com/user-attachments/assets/0233d7fb-937d-42ba-8110-586f26d9d394)


# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 
# EX-03- Operators-Expressions

## AIM:
Debug the given C program to find the number of years based on principle amount, rate of interest & simple interest.

## ALGORITHM:
1.Start the program and declare variables for principal (P), rate (R), interest (SI), and time (T).
2.Input values for principal, rate, and simple interest.
3.Use the formula T = SI / (P * R / 100) to calculate the number of years.
4.Display the result and end the program.

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

![image](https://github.com/user-attachments/assets/70c4e130-47b4-44fd-a2a7-e6f15f2494ba)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.



# EX-04- Using Conditional Statements

## AIM:
Write a C program to count the number of digits without using a loop

## ALGORITHM:
1.Start the program and define a recursive function to count digits.

2.In the function, check if the number is 0; if so, return 0.

3.Otherwise, return 1 + recursive call with number / 10.

## PROGRAM:
```
#include <stdio.h>

int countDigits(int num) {
    // Base case: if num is 0, return 0
    if (num == 0) {
        return 0;
    }
    // Recursive case: count this digit and call the function with num / 10
    return 1 + countDigits(num / 10);
}

int main() {
    int number;

    scanf("%d", &number);
    
    // Handle the case where the number is 0
    if (number == 0) {
        printf("Number: 1\n");
    } else {
        printf("Number:%d\n", countDigits(number < 0 ? -number : number));
    }
    
    return 0;
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/050a5b16-840d-4387-b638-dc66eeafc223)

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
![image](https://github.com/user-attachments/assets/b6a82338-68d2-4dfd-ad30-b1b952920cb6)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

