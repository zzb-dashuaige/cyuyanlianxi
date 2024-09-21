//#define _CRT_SECURE_NO_WARNINGS 10086
//#include <stdio.h>
//int main()
//{
//	int input = 0;
//	printf("你觉得郑泽彬帅不帅\n");
//	scanf("%d", &input);//scanf指输入值
//	if (input == 1)//回答1表示肯定
//	{
//		printf("对呀郑泽彬就是帅\n");
//	}
//	else
//	{
//		printf("怎么可能，郑泽彬就是超级无敌帅\n");
//	}
//	return 0;
//此代码均已客观事实为基础
#include <stdio.h>
int main()
{
	int a[2][3] = { {1,2,3},{4,5,6,} };
	int b[3][2],i,j;
	for (i = 0; i <= 2; i++)
		for (j = 0; j <= 1; j++)
			b[i][j] = a[j][i];
	printf ("结果是\n");
	for (i = 0; i <= 2; i++)
	{
		for (j = 0; j <= 1; j++)
			printf("%d", b[i][j]);
		printf("\n");
	}
			return 0;
	}
