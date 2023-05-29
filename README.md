# lab1.1
Липчанский Дмитрий, ИТС-б-о-22-1, Основы кроссплатформенного программирования.

Программа:
# include <stdio.h>
# include <math.h> 
#include <conio.h>
#include <locale.h>
int main()
{
float x, sum;
	setlocale(LC_ALL, "Ruassian");
	int i,f, n, k;
	sum = 0;
	const double e = 2.7;
printf("Write x: ");
	scanf_s("%f", &x);
	printf("write n: ");
	scanf_s("%d", &n);
for (i = 2; i <= n; i++)
	{
k = (i+1);
		for (f = 1; f <= i; f++)
		{
			k *= f;
		}
		sum += (pow((e), x) - i) / k;
		printf("sum=%f\n", sum);
}
	return 0;
       }

