# rohit-phython-assignment

python programs given on 23-09-19

#1).numbers divisible by 7 but not 5 between 2000 and 3200

print("numbers divisible by 7 but not 5 between 2000 and 3200 ") a=2000 while(a<=3200): if(a%7==0 and a%5!=0): print(a) a+=1

#2). program to compute factorial

print("enter number to find factorial") a=int(input()) k=a-1 while(k>0): a*=k k-=1 print(a)

#3). program to print i,i*i

num=int(input(" enter the number : ")) n=1 while(n<=num): print(n,':',n*n) n+=1

#4). program to print reverse

num=int(input("enter number : ")) num2=0 r=0 while(num>0): r=num%10 num2=(num2*10)+r num=int(num/10) print(num2)

#5). program to print sum of n numbers

num=int(input("enter the number n : ")) k=0 n=0 while(k<=num): n+=k k+=1 print(n)

#6). program to print sum of n numbers(odd and even separately)

num=int(input("enter the number n : ")) k=0 odd=0 even=0 while(k<=num): if(k%2==0): even+=k else: odd+=k k+=1 print("odd : ",odd ) print("even : ",even)

#7). program to print natural numbers in reverse

num=int(input("enter the number n : ")) while(num>0): print(num) num-=1

#8). program to print first and last digit of a number

num=int(input("enter number : ")) last=(num%10) while(num>9): num=int(num/10) print(num) print(last)

#9). program to print product of first and last digit of a number

num=int(input("enter number : ")) last=(num%10) while(num>9): num=int(num/10) pro=int(last*num) print("product : ",pro)

#10). program to print name of a single digit numbers n=int(input("enter number of digits : ")) while(n>0): num=int(input("enter a single digit number : ")) if(num==0):print(" ZERO ") if(num==1):print(" ONE ") if(num==2):print(" TWO ") if(num==3):print(" THREE ") if(num==4):print(" FOUR ") if(num==5):print(" FIVE ") if(num==6):print(" SIX ") if(num==7):print(" SEVEN ") if(num==8):print(" EIGHT ") if(num==9):print(" NINE ") n-=1

#11). program to print power of a number

num=int(input("enter a number : ")) power=int(input("enter the power : ")) num2=num power2=power while(power>1): num=num*num2 power-=1 print(num2,"^",power2,"=",num)

#12). program to print if a number is prime or not

num=int(input("enter a number : ")) n=2 k=0 while(n<num): if(num%n==0):k=1 n+=1 if(k==0):print(" PRIME ") else:print(" NOT PRIME ")
'''y=[]
for x in range(2000,3201):
    if(x%7==0 and x%5!=0):
        y.append(x)
    print(x) 
#2    
    fac=1 
    x=int(input("enter number :"))
    for i in range(1,x+1):
        fac=fac*i 
        print("factorial is : ",fac)
        #3
    n=int(input("enter number :")) 
    dic={}
    for i in range(1,n+1):
        dic[i]=i*i 
        print(dic) 
        #4
    x=input("enter the comma seperated sequence")
    y=x.split(',')
    print(y) 
#5
x=input("enter the seq")
y=x.split(",")
c=50
h=30 
q=[]
for i in y:
    j=int(i)
    q.apend(2*c*j/h)
print(q)'''
 
 #6 
rw=int(input("enter  row"))
cl=int(input("enter columns"))
q=[]
p=[]
for i in range(1,rw+1):
    p.clear
for j in range(1,cl+1):
    p.append(i*j)
    q.append(p.copy())
    print(q)
'''#9 
print("enter no") 
c=[]
while true: 
    try:
        line=input()
        except eof error: 
            break
        c.append(line.upper())
        print(c)'''
Q1.
#include <stdio.h>
int main()
{
    int n;
    printf(" Enter a Number  :  ");
    scanf("%d",&n);
    if((n%2)!=0)
      printf(" Wierd ");
      else
        {
          if((n>=2)&&(n<=5))
            printf(" Not Weird ");
            else
              if((n>=6)&&(n<=20))
                printf(" Weird ");
                  else
                    if(n>20)
                      printf(" Not weird");
        }
    return 0;
}
Q2.
#include <stdio.h>
int main()
{
    int n,m;
    printf(" Enter a Number  :  ");
    scanf("%d",&n);
    printf(" Enter a Number  :  ");
    scanf("%d",&m);
    if(n>m)
       printf("Greater number is  :  %d",n);
       else
         printf("Greater number is  :  %d",m);
    return 0;
}
Q3.
#include <stdio.h>
int main()
{
    int n,m,b;
    printf(" Enter first Number  :  ");
    scanf("%d",&n);
    printf(" Enter second Number  :  ");
    scanf("%d",&m);
    printf(" Enter third Number  :  ");
    scanf("%d",&b);
    if(n>m&&n>b)
       printf("Greater number is  :  %d",n);
         else
           if(m>n&&m>b)
              printf("Greater number is  :  %d",m);
                else
                  printf("Greater number is  :  %d",b);
    return 0;
}
Q4.
#include <stdio.h>
int main()
{
    int n;
    printf(" Enter a Number  :  ");
    scanf("%d",&n);
    if(n>0)
       printf("Positive number ");
         else
           if(n<0)
            printf("Negative number ");
              else
                if(n==0)
                 printf("Number is Zero ");
    return 0;
}
Q5.
#include <stdio.h>
int main()
{
    int n;
    printf(" Enter a Number  :  ");
    scanf("%d",&n);
    if((n%5==0)&&(n%11==0))
       printf(" Divisible by 5 and 11");
         else
            printf(" Not divisible by 5 and 11");
    return 0;
}
Q6.
#include <stdio.h>
int main()
{
    int n;
    printf(" Enter a Number  :  ");
    scanf("%d",&n);
    if(n%2==0)
       printf(" Even Number");
         else
            printf(" Odd Number");
    return 0;
}
Q7.
#include <stdio.h>
int main()
{
    int n;
    printf(" Enter year  :  ");
    scanf("%d",&n);
    if(n%4==0)
       printf(" Leap year");
         else
            printf(" Not Leap year");
    return 0;
}
Q8.
#include <stdio.h>
int main()
{
    char n;
    printf(" Enter a character (alphabet,number or operator)  :  ");
    scanf("%c",&n);
    if(((n>=97)&&(n<=122))||((n>=65)&&(n<=90)))
       printf(" Character Is An Alphabet");
         else
           printf(" Character Is Not An Alphabet");
    return 0;
}
Q9.
#include <stdio.h>
int main()
{
    char n;
    printf(" Enter an alphabet  :  ");
    scanf("%c",&n);
    if((n=='a')||(n=='e')||(n=='i')||(n=='o')||(n=='u')||(n=='A')||(n=='E')||(n=='I')||(n=='O')||(n=='U'))
       printf(" Alphabet is a vowel ");
         else
           printf(" Alphabet is a consonent ");
    return 0;
}
Q10.
#include <stdio.h>
#include<ctype.h>
int main()
{
    char n;
    printf(" Enter a character (alphabet,number or operator)  :  ");
    scanf("%c",&n);
    if(isalpha(n))
       printf(" Character is an Alphabet");
         else
           if(isdigit(n))
             printf(" Character is a digit");
               else
                 printf(" Character is a special character");
    return 0;
}
Q11.
#include<stdio.h>
#include<ctype.h>
int main()
{
    char n;
    printf(" Enter an alphabet  :  ");
    scanf("%c",&n);
    if(isupper(n))
       printf(" Uppercase alphabet");
         else
           if(islower(n))
             printf(" lowercase alphabet");
    return 0;
}
Q12.
#include<stdio.h>
#include<ctype.h>
int main()
{
    int n;
    printf(" Enter Week number (1-7)  :  ");
    scanf("%d",&n);
    switch(n)
    {
        case 1: printf("Monday");
                break;
        case 2: printf("Tuesday");
                break;
        case 3: printf("Wednesday");
                break;
        case 4: printf("Thursday");
                break;
        case 5: printf("Friday");
                break;
        case 6: printf("Saturday");
                break;
        case 7: printf("Sunday");
                break;
        default: printf("!!**Invalid input**!!");
    }
    return 0;
}
