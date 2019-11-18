# ** PROGRAMMING FOR PROGRAM SOLVING ESC-18105 **
## NAME- * KISHAN TIWARI *
## ROLL NO-* 1921056 *
## BRANCH-* B.Tech(IT) *
## SECTION-* A2 *
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## ** DEPARTMENT OF INFORMATION TECHNOLOGY **
# ** GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA(PUNJAB) **








## 1.program to get average of five numbers.

#include<stdio.h>

 int main() 
                                          
 {

        int a,b,c,d,e;   
                                    
        scanf("%d",&a);

        scanf("%d",&b);

        scanf("%d",&c); 
                                     
        scanf("%d",&d);

        scanf("%d",&e);

        int f=(a+b+c+d+e)/5; 
                                
        printf("average of five numbers:%d\n \n",f);
 }

## //Output of the program\\

5

5  
                                                   
5

5

5

average of five numbers:5

## 2. Addition .

#include<stdio.h>

int main()

{
                                                                  int a=100;
        int b=10;

        int c;

        c=a+b;

        printf("\n%d\n\n",c);

        return 0;

}


## //Output \\


110


## 3.Arithmetic.

#include<stdio.h>

int main()

{

int a=9,b=4,c;

c=a+b;

printf("a+b = %d \n",c); 

c=a-b;

printf("a-b = %d \n",c);

c=a*b; 

printf("a*b = %d \n",c);

c=a/b;

printf("a/b = %d \n",c);

c=a%b; 
 
printf("remainder when a divided by b = %d \n",c);

return 0;

}

## // Output\\

a+b = 13

a-b = 5

a*b = 36

a/b = 2

remainder when a divided by b = 1


## 4.Array .

#include<stdio.h>

int main()

{

int n[10];
  
int i,j;

for ( i=0;i<10;i++)

{   

 n[i]=i+100;

}

for (j=0;j<10;j++)

{

printf ("element[%d] = %d\n",j,n[j]);

}

return 0;

}

## //Output\\

element[0] = 100

element[1] = 101
  
element[2] = 102

element[3] = 103

element[4] = 104

element[5] = 105 
  
element[6] = 106

element[7] = 107

element[8] = 108

element[9] = 109

## 5.Assignment.

include<stdio.h>  
 
int main()

{   
                                                 $
 c=a;

 printf("c=%d\n",c); 

 c+=a;

 printf("c=%d\n",c);

 c-=a;

 printf("c=%d\n",c);

 c*=a;

 printf("c=%d\n",c);

 c%=a;

 printf("c=%d\n",c);

 c/=a;

printf("c=%d\n",c);

return 0;

}

## //Output\\

c=5

c=10   
                                               c=5
c=25

c=0

c=0

## 6.Calculator.

puts("|-----------------|");  

puts("| 9 | 8 | 7 |     |");

puts("|___________|  +  |");

puts("| 6 | 5 | 4 |     |");

puts("|-----------------"); 

puts("| 3 | 2 | 1 |  -  |");

puts("|___________|_____|");

puts("|     0     |  *  |");

puts("|_________________|");

}

## //Output\\

 _________________
|                 |
|-----------------| 
| 9 | 8 | 7 |     |
|___________|  +  |
| 6 | 5 | 4 |     |
|-----------------
| 3 | 2 | 1 |  -  |
|___________|_____|
|     0     |  *  |
|_________________|

## 7.Eventable.

#include<stdio.h>

int main()

{

int i,n;

printf("\nenter a number : ");

scanf("%d",&n);

if(n%2==0)

{

for(i=0;i<=10;i++)

{

printf(" %d × %d = %d\n",n,i,n*i);

}

}

else

printf(" number is not a multiple of even number\n");

return 0;

}

## //Output\\

enter a number : 4

 4 × 0 = 0

 4 × 1 = 4

 4 × 2 = 8 
 
 4 × 3 = 12

 4 × 4 = 16

 4 × 5 = 20

 4 × 6 = 24

 4 × 7 = 28

 4 × 8 = 32

 4 × 9 = 36

 4 × 10 = 40

## 8.Total experience.

#include<stdio.h>

int main(){

printf("enter number of employees:");

int n;

scanf("%d",&n);

int exp,sum=0;

for(int i=1;i<=n;i++){

printf("enter experience of %d th employees (in years$

scanf("%d",&exp);

sum=sum+exp;

}

printf("%d\n",sum);

return 0;}

## //Output\\

enter number of employees:6

enter experience of 1 th employees (in years)  :5

enter experience of 2 th employees (in years)  :5

enter experience of 3 th employees (in years)  :5

enter experience of 4 th employees (in years)  :5

enter experience of 5 th employees (in years)  :5

enter experience of 6 th employees (in years)  :5

30

## 9. Factorial.

#include<stdio.h>

int main()

{

int a,i,f=1;

printf("enter the number :");

scanf(" %d",&a);

for(i=1;i<=a;i++)

f=f*i;

printf(" factorial of given number :%d",f);

}

## //Output\\

enter the number :6
factorial of given number :720

## 10.Farenheit.

#include<stdio.h> 

int main()

{  

int f;

printf(" value of farenheit = "); 
 
scanf("%d",&f);

int celcious = 273+f;// f= farenheit

printf("value of celcious given out to be = %d",celci$

return 0;

}

## //Output\\

value of farenheit = 273

value of celcious given out to be = 546


## 11.Fizz.

#include<stdio.h>

int main()
{
int a,b,c;

printf("enter the value :",a);

scanf("%d",&a);

if(a%3==0) 

printf("fizz");

if(a%5==0)

printf("buzz");

else if (a%15==0)

printf("fizz buzz ");

else ("%d",a);

return 0; 

}

## //Output\\

enter the value :6

fizz 

## 12.Floatexample

#include<stdio.h>

int main() 

  {   
                           
float age;

age=18.6;

printf("%f\n" , age);

    }

## //Output\\

18.6000  

## 13.Function

#include<stdio.h>

int message();

int name();

int department();  

int main()

{

 message();

 name();

 department();

 face();

}

int message()

{

puts("    GURU NANAK DEV ENGINEERING COLLEGE  ");

}

int name()

{

puts("    ------------------------"); 

puts("   |name : kishan tiwari|");

puts("    ------------------------");

}

int department() 

  {                                   

puts("     branch : IT (A2)"); 

                       } 
                                                    
int face()

{

puts(" ____"); 
                              
puts(" ____");

puts("//+  +\\")

 puts("| *   |");

puts("\\ -- //");}

## //Output\\

  GURU NANAK DEV ENGINEERING COLLEGE

    ------------------------

   |name : kishan tiwari|

    ------------------------

     branch : IT (A2)

 ____

//+  +\

|   *  |

\  --/ 

## 14.

                                                             
