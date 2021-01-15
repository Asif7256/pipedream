#include <stdio.h>
int main( ){
	int i,j;
	float s = 0.0;
	printf("Input the value of j: ");
	scanf("%d", &j);

	for(i = 1; i <= j; i++){
		printf("1/%d + ", i);
		s = s + 1/(float)i;
	}
	printf("Result = %f\n", s);
	return 0;
}
