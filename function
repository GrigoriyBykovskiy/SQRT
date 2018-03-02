#include "stdafx.h"
#define e 0.0001
float mysqrt(float x);
int main()
{
	float a;
	printf("Hello. Please write your number>2:");
	scanf_s("%f",&a);
	printf("Sqrt:=%.3f\n",mysqrt(a));
	return 0;
}
float mysqrt(float x) {
	float l1=1, l2=x,q;
	while ((l2-l1)>e) {
		q =(l1+l2)/2;
		if (q*q == x) break;
		if (q*q > x) l2 = q;
		else l1 = q;
	}
	return q;
}
