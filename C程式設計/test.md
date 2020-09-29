



# 函數
```
#include <stdio.h>
 
/* 函式宣告 */
int max(int num1, int num2);
 
int main ()
{
   /* 區域變數定義 */
   int a = 100;
   int b = 200;
   int ret;
 
   /* 調用函數來獲取最大值 */
   ret = max(a, b);
 
   printf( "Max value is : %d\n", ret );
 
   return 0;
}
 
/* 函數返回兩個數中較大的那個數 */
int max(int num1, int num2) 
{
   /* 區域變數聲明 */
   int result;
 
   if (num1 > num2)
      result = num1;
   else
      result = num2;
 
   return result; 
}

```
## 遞迴函數
```
#include <stdio.h>
 
double factorial(unsigned int i)
{
   if(i <= 1)
   {
      return 1;
   }
   return i * factorial(i - 1);
}


int  main()
{
    int i = 15;
    printf("%d 的階乘為 %f\n", i, factorial(i));
    return 0;
}
```
```
#include <stdio.h>
 
int fibonaci(int i)
{
   if(i == 0)
   {
      return 0;
   }
   if(i == 1)
   {
      return 1;
   }
   return fibonaci(i-1) + fibonaci(i-2);
}
 
 
int  main()
{
    int i;
    for (i = 0; i < 10; i++)
    {
       printf("%d\t\n", fibonaci(i));
    }
    return 0;
}

```
