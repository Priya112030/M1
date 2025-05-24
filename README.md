
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.


## PROGRAM:
```
#include <stdio.h>
int main()
{ char a,b,c;
  scanf("%c%c%c",&a,&b,&c);
  printf("The reverse of %c%c%c is %c%c%c",a,b,c,c,b,a);
  return 0;
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/79636502-e1a4-42f0-9cb1-e29ec9bec223)

## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read a, b value and find the greatest value using  if-else
# ALGORITHM:
```
Step 1: Start
Step 2: Declare two integer variables: a and b
Step 3: Read two integers from the user using scanf
Step 4: Compare the values:
If a < b, then print "B is greatest."
Else, print "A is greatest."
Step 5: End
```

# PROGRAM
```
# include <stdio.h>
int main()
{
    int a;
    int b;
    scanf("%d%d",&a,&b);
    if(a<b)
    printf("B is greatest.");
    else
    printf("A is greatest.");
    return 0;

}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/24566f03-51fc-4d86-8fe8-e25cd4dc2249)


# RESULT:
Thus the program to read a,b values an the greatest value has been executed successfully.
 
 
 
 # EX-03- Operators-Expressions
## AIM:
Write a program to find minimum value between two  numbers using conditional operator or ternary operator.

## ALGORITHM:
```
Step 1: Start
Step 2: Declare three integer variables: a, b, and m
Step 3: Read values for a and b from the user
Step 4: Use the ternary operator to find the smaller number:
 If a < b, then m = a
 Else, m = b
Step 5: Print the result: "Minimum between a and b is m"
Step 6: End
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
Thus the program to find minimum value between two  numbers using conditional operator or ternary operator has been executed successfully.


# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
```
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 0.
4.	If the condition in the if statement is true, print a message 'False'.
5.	Otherwise, print a message "  ".
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

