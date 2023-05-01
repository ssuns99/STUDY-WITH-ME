# STUDY-WITH-ME
Study things you could be the best 

#include <stdio.h>

// 1번. A+B - 8 (https://www.acmicpc.net/problem/11022)
int main()
{
	int x = 0;
	int a[100], b[100] = { 0, };
	int i = 1;

	scanf_s("%d", &x); //테스트횟수

	for (i = 1; i <= x; i++)
	{
		scanf_s("%d %d", &a[i], &b[i]);
	}

	for (i = 1; i <= x; i++)
	{
		printf("Case #%d: %d + %d = %d\n", i, a[i], b[i], a[i] + b[i]);
	}
	
	return 0;
}
