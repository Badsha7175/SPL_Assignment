# SPL_Assignment
## This is my first github folder
### Learn from sajjat sir

`home` hello
```c
#include<stdio.h>
int main( )
{
        int n;
        printf("Enter a number: ");
        scanf("%d",&n);

        while(n>0)
        {
            int x = n%10;
            printf("%d \t",n);
            n = n / 10 ;
            printf("%d",x);

        }

        return 0;
}
```
