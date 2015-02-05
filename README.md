# fibonaci
#include<bits/stdc++.h>
#include<conio.h>

int fib(int n){
	if(n==1 || n==0) return 1;
	
	else return (fib(n-2)+fib(n-1)); 
	}
	
int main(){
	int a;
	scanf("%d",&a);
	printf("%d",fib(a));
	getch();
}
