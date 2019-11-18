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
printf("\nenter a number : ");                        scanf("%d",&n);
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
