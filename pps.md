![GNE](https://raw.githubusercontent.com/VIRAJAHLUWALIA/ppsreport/master/sm_logo.png)
# PROGRAMMING FOR PROBLEM SOLVING
-------
Submitted By-BRAJ MOHAN SINGH

Class Roll No.-1916088

Uni. Roll No.-1905090

Branch-Electrial

Section-B

Batch-2019-2023

-------
EXPERIMENT NO.-1
WRITE A CODE TO PRINT THE NAME OF YOUR COLLEGE.
```C
#include<stdio.h>
int main()
{
puts("GURU NANAK DEV ENGINEERING COLLEGE");
}
```
----
EXPERIMENT NO.-2
Write a code to print FOX.
```c
#include<stdio.h>
int main()
{
    puts("########      ########      ####             ####");
    puts("##        ####          ####     ###       ###");
    puts("##        ####          ####        ###  ###");
    puts("######    ####          ####          ####");
    puts("##        ####          ####        ###  ###");
    puts("##        ####          ####      ###      ###");
    puts("##             ########        ####          ####");
}
```
------
EXPERIMENT NO.-3
Write a C program to print a big ' C '.
```c
#incude<stdio.h>
int main()
{
puts(" ######");
puts("##    ##");
puts("#");
puts("#");
puts("#");
puts("#");
puts("#");
puts("##     ##");
puts(" ######");
}
```
------
EXPERIMENT NO.-4
Design a code to execute addition of two numbers.
```c
#include<stdio.h>
int main()
{
    int a,b,c;
scanf("%d", &a);
scanf("%d", &b);
c=a+b;
printf("%d",c);
return 0;
}
```
-------
EXPERIMENT NO.-5
Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```c
#include<stdio.h>
int main()
{
int a,b;
scanf("%d", &a);
scanf("%d", &b);
if(a<b)
{
printf("%d", a);
}
else
{
printf("%d", b);
}
}
```
-------
EXPERIMENT NO.-6
Write a C program to print the  characters in a reverse way without using any predefined function.
```c
#include<stdio.h>
int main()
{
char x,m,l;
scanf("%c",&x);
scanf("%c",&m);
scanf("%c",&l);
x,m,l=l,m,x;
printf("%c",l);
printf("%c",m);
printf("%c",x);
}
```
------
Experimenr No.-7
Write a code for FIZZ BUZZ GAME.
```c
#include <stdio.h> 
  
int main(void) 
{ 
    int i; 
    scanf("%d",&i);
    
        // number divisible by 3 and 5 will 
        // always be divisible by 15, print  
        // 'FizzBuzz' in place of the number 
        if (i%15 == 0)         
            printf ("FizzBuzz\t");     
          
        // number divisible by 3? print 'Fizz' 
        // in place of the number 
        else if ((i%3) == 0)     
            printf("Fizz\t");
          
        // number divisible by 5, print 'Buzz'   
        // in place of the number 
        else if ((i%5) == 0)                        
            printf("Buzz\t");                  
      
        else // print the number             
            printf("%d\t", i);                  
  
  
    return 0; 
} 
```
-------
Experiment no.-8
Write a code to print your name.
```c

#include<stdio.h>
int main() {

puts("**************");
puts("VIRAJ");
puts("**************");

return 0;
}
```
------
Experiment no.-9
Write a C program to compute the perimeter and area of a rectangle 
```c

#include<stdio.h>
int main()                                                                  
{
int a,p,l,b;
scanf("%d",&l);
scanf("%d",&b);
p=2*(l+b);
a=l*b;
printf("%d\n",p);
printf("%d\n",a);
}
```
------
Experiment no.-10
Design a code to execute addition of two numbers if the sum is even.

```c
#include<stdio.h>
int main()
{
int a,b,c;
scanf("%d",&a);
scanf("%d",&b);
c=a+b;
if(c%2==0)
{
    printf("%dis even",c);
}
else
{
    printf("%dis odd",c);
}
}
```
------
Experiment no.-11
Problem: Design a code to mark 'Present' if student entered in a hall before 8:35 and
marked 'Late' before 8:45 otherwise marked 'Absent'.
```c
#include<stdio.h>
int main()
{
    float time;
    scanf("%f",&time);
    if(time>8.14&&time<8.36);
    printf("present");
    {
        if(time>=8.36&&time<=8.45)
        printf("late");
        else
        {
            if(time>8.45&&time<9.00)
            printf("absent");
            else
            {
                if(time==8.00&&time<8.14)
                printf("sorry gates closed");
                else
                {
                    if(time>7.00&&time<8.00)
                    printf("wrong time");
                    else
                    {
                        if(time>=9.00)
                        printf("sorry gate closed");
                        else
                        {
                            if(time>=1.00&&time<9.00)
                            printf("wrong time");
                        }
                        
                    }
                }
            }
        }
    }
}
```
------
Experiment no.-12
Write a code to convert temperature from Fahrenheit scale to centigrade scale.
```c
#include<stdio.h>
#include<math.h>
int main()
{
    float fr,cent;
    printf("enter the temperature in fahrenheit :");
    scanf("%f",&fr);
    cent=5/9*(fr-32);
    printf("TEMPERATURE IN CENTIGRADE : %f",cent);
}
```
------
Experiment no.-13
Write a code to find the factorial of a number.
```c
#include<stdio.h>
#include<math.h>
int main()
{
    int a,i,f=1;
    printf("enter the no");
    scanf("%d",&a);
    {
        for(i=1;i<=a;i++)
        f=i*f;
        printf("factorial of%d=%d",a,f);
        
    }
}
```
-------
Experiment no.-14
Write a code to print table of any number.
```c
#include<stdio.h>
#include<math.h>
int main()
{
    int n,i;
    printf("enter the no . ");
    scanf("%d",&n);{
    for(i=1;i<=10;i++)
    printf("\n%d x %d=%d",n,i,n*i);}
}
```
-------
Experiment no.-15
Write a code to display the number is prime or not.
```c
#include<stdio.h>
int main()
{
    int i,n, sum=0;
    printf("enter a possitive integer");
    scanf("%d",&n);
    for(i=2;i<=n/2;++i)
  {
      if(n%i==0)
   { sum=1;
    break;
  if(n==1)
  {
   printf("its neither prime nor composite");
  }
  else
  {
      if(sum==0)
      printf("%dis a prime no",n);
      else
      printf("%d is composite no",n);
  }
  
}
}
}
```
-------
Experiment no.-16
To find quotient and remainder
```c
#include <stdio.h>

int main() {
    
int a,b,r,q;

printf("\nEnter the Dividend:");
scanf("%d",&a);

printf("\nEnter the divisor:");
scanf("%d",&b);

r=a%b;
q=a/b;

printf("\nRemainder: %d",r);
printf("\nQuotient: %d",q);

return 0;
}
```
-----
Experiment no.-17
Find greatest of three number
```c
#include<stdio.h>
int main() {
int x, y, z, large;
        
 printf(" Enter any three integer numbers for x, y, z :  ") ;

scanf("%d %d %d", &x, &y, &z) ;

large = (x > y ? ( x > z ? x : z) : (y > z ? y : z)) ;

printf("\n\n Largest  or biggest or greatest or maximum among 3 numbers using Conditional ternary Operator :  %d", large) ;
       
 return 0;
}
```
-------
Experiment no.-18
Program to assign grade to student according to percentage.
```C
#include<stdio.h>
int main() { 
    
  int s1,s2,s3,s4,s5,agg;
  float perc;

  printf("Enter the Marks in 5 Subjects Respectively:\n");

scanf("%d%d%d%d%d",&s1,&s2,&s3,&s4,&s5);

agg=s1+s2+s3+s4+s5; // Aggregate Marks
  
  perc=agg/500.0*100;  // Perc Marks

  if(perc>=90)
  {
      printf("\nA");
      
  }
  
  else if (perc>=80 && perc<90)
  { 
      printf("\nB");
      
  }
  
  else if(perc>=70 && perc<80)
  {
      printf("\nC");
      
  }
  
  else if(perc>=60 && perc<70)
  { 
      printf("\nD");
  }
  else if(perc>=50 && perc<60)
  {
      printf("\nE");
  }
  else 
     {
          printf("\nScope of Improvement....");
    } 
    return 0;
}
```
-------
Experiment no.-19
Program to print roots of quadratic equation.
```C
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
 
int main() {
    float a, b, c, root1, root2;
    float realp, imagp, disc;
 
printf("Enter the values of a, b and c \n");
    scanf("%f %f %f", &a, &b, &c);
    
/* If a = 0, it is not a quadratic equation */

if (a == 0 || b == 0 || c == 0)
    {
        printf("Error: Roots cannot be determined \n");
        exit(1);
    }
    else
    {
        disc = b * b - 4.0 * a * c;
        if (disc < 0)
        {
            printf("Imaginary Roots\n");
            realp = -b / (2.0 * a) ;
            imagp = sqrt(abs(disc)) / (2.0 * a);
            printf("Root1 = %f  +i %f\n", realp, imagp);
            printf("Root2 = %f  -i %f\n", realp, imagp);
        }

else if (disc == 0)
        {
            printf("Roots are real and equal\n");
            root1 = -b / (2.0 * a);
            root2 = root1;
            printf("Root1 = %f\n", root1);
            printf("Root2 = %f\n", root2);
        }

else if (disc > 0 )
        {
            printf("Roots are real and distinct \n");
            root1 =(-b + sqrt(disc)) / (2.0 * a);
            root2 =(-b - sqrt(disc)) / (2.0 * a);
            printf("Root1 = %f  \n", root1);
            printf("Root2 = %f  \n", root2);
        }

}
   return 0;
}
```
-------
Experiment no.-20
Program to check year is leap or not.
```C
#include<stdio.h>
int main() { 

  int year,temp;

  printf("Enter teh year:");
  scanf("%d",&year);

  temp=year%4;

  if(year%100==0)
  {
     if(year%400==0)
     printf("\nLeap year...");
  }

  else
  {
    if(year%4==0)
    printf("\nLeap year...");

else
    printf("\nNot a Leap year...");
   }
  
  return 0;
}
```
--------
Experiment no 21
Write a code to display the number is prime or not.
```c
#include<stdio.h>
int main()
{
    int i,n, sum=0;
    printf("enter a possitive integer");
    scanf("%d",&n);
    for(i=2;i<=n/2;++i)
  {
      if(n%i==0)
   { sum=1;
    break;
  if(n==1)
  {
   printf("its neither prime nor composite");
  }
  else
  {
      if(sum==0)
      printf("%dis a prime no",n);
      else
      printf("%d is composite no",n);
  }
  
}
}
}
```
------
Experiment no 22
Write a code to print a range of prime number between some range.
```c
#include<stdio.h>
#include<math.h>
int main()
{
    int x,y,count=0,k;
    scanf("%d%d",&x,&y);
    for(int i=x;i<=y;i++)
    {
        for(int k=1;k<=i;k++)
   {
       if(i%k==0)
       count++;
   }
   {
     if(count==2)
     printf("\n%d",i);
     count=0;
   }
   printf("\n");
}
}
```
