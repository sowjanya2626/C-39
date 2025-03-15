# C-39
Nested Recursion 
#include<stdio.h>
int nest(int n){
	if(n>100) return n-10;
	return nest(nest(n+11));
}
int main()
{
	printf("%d",nest(75));
	return 0;
}                                  
