#
```
for 
while
do .. while
```
## for loop
```

#include <stdio.h>

int main(void)
{
	int n;
	int add = 0;
	int i;

	scanf("%d", &n);

	for(i = 1; i <= 10; i++)
		add += i;

	printf("the result is %d\n", add);

	return 0;
}
```
```
#include <stdio.h>

int main(void)
{
	int i;
	int sum;
	int n;

	scanf("%d", &n);

	sum = 0;
	for(i = 1; i <= n; i++)
		sum += i;

	printf("the result is : %d\n", sum);

	return 0;
}
```
# while loop
```
#include <stdio.h>

int main(void)
{
	int n;
	int mul = 1;
	int i;

	scanf("%d", &n);
	
	i = 1;
	while(i <= n){
		mul *= i;
		i++;
	}

	printf("the result is %d\n", mul);

	return 0;
}
```

# do ... while  loop
```
#include <stdio.h>

int main(void)
{
	int n;
	int mul = 1;
	int i;

	scanf("%d", &n);
	
	i = 1;
	do{
		mul *= i;
		i++;
	}while(i <= n);

	printf("the result is %d\n", mul);

	return 0;
}

```
# 無窮迴圈
```
#include <stdio.h>
 
int main ()
{
   for( ; ; )
   {
      printf("該迴圈會永遠執行下去！\n");
   }
   return 0;
}

```
