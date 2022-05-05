//  04/05/22
// Q1) Program to show that macro expansion can be a string constant
#include <iostream>
#define MSSG "I understand the use of #define\n"

main() {
    printf(MSSG);
       }
  
  
  //Q2) Program to understand macros with arguments
  
  #include <iostream>
#define SUM(x,y)  ((x) + (y))
#define PROD(x,y)  ((x) * (y))
main()
{
    int l,m,i,j,a=5,b=3;
    float p,q;
    l=SUM(a,b);
    m=PROD(a,b);
    i=SUM(4,6);
    j=PROD(4,6);
    p=SUM(2.2,3.4);
    q=PROD(2.2,3.4);
    printf("l=%d,m=%d,i=%d,j=%d,p=%.1f,q=%.1f,q=%.1f\n",l,m,i,j,p,q);

}

  //Q3
  
  #define MAX(x,y)  ((x)>(y)) ? (x) : (y)
#define MIN(x,y)  ((x)<(y)) ? (x) : (y)
#define ISLOWER(c) (c>=97 && c<=122)
#define ISUPPER(c)  (c>=65 && c<=90)
main()
{
    int l,m,i,j,a=5,b=7,r;
    char c;
    float p,q;
    l=SQUARE(a);
    m=MIN(a,b);
    i=SQUARE(4);
    j=MAX(4,6);
    p=SQUARE(b);
    q=ISLOWER(c);
    r=ISLOWER(c);
    printf("l=%d,m=%d,i=%d,j=%d,p=%.1f,q=%.1f,q=%.1f\n,r=%d",l,m,i,j,p,q,r);

}

