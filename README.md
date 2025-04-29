
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
```
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.
```	

## PROGRAM:
```
# include <stdio.h>
int main()
{ char r;
  scanf("%c",&r);
  printf("ASCII value of %c is %d",r,r);
  return 0;
}
```


## OUTPUT:

![Screenshot 2025-04-29 064252](https://github.com/user-attachments/assets/6d557f34-0860-49ad-bc73-679d6b09398d)

## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
```
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.
```

# PROGRAM
```
# include <stdio.h>
 int main(){
     int a; 
     int b;
     scanf("%d%d",&a,&b);
     if(a==40)
     {printf("The first number is equal to 40\n");
     
        if(b==100)
        printf("The second number is equal to 100");
        else
        printf("The second number is NOT equal to 100");
     }
     else
     printf("The first number is NOT equal to 40");
     return 0;
}
```
# OUTPUT:

![Screenshot 2025-04-29 064804](https://github.com/user-attachments/assets/3dff2892-efe1-499e-b690-16bd83a4b5c7)

# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 
 # EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
```
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.
```

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b,m;
    scanf("%d%d",&a,&b);
    m=(a<b)?a:b;
    printf("Minimum between %d and %d is %d",a,b,m);
    
    
    return 0;
    
}
```

## OUTPUT:

![Screenshot 2025-04-29 065558](https://github.com/user-attachments/assets/a8b392a9-4a47-45b2-adb3-5a5642e07267)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.


# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
```
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.
```

## PROGRAM:
```
# include<stdio.h>
   int main()
{   int a;
   scanf("%d",&a);
   if(a==0)
   printf("FALSE");
   else
   printf("  ");
   return 0;
}
```

## OUTPUT:

![Screenshot 2025-04-29 070135](https://github.com/user-attachments/assets/d8acbf10-378a-4407-adaa-52286eea51de)


## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
```
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
```
## PROGRAM:
```
#include <stdio.h>
int main(){
  float a,b,c,d,e;
  float t,m,p;
  scanf("%f%f%f%f%f",&a,&b,&c,&d,&e);
  t=(a+b+c+d+e);
  m=t/5;
  p=(t/500)*100;
  printf("Total marks = %.2f\n",t);
  printf("Average marks = %.2f\n",m);
  printf("Percentage = %.2f\n",p);
  return 0;
}
```

## OUTPUT:

![Screenshot 2025-04-29 065224](https://github.com/user-attachments/assets/9547ba12-7d43-4dcb-ad6c-dd0289238416)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

