# Pattern-printing
#include<stdio.h>
void main(){
int n;
printf("enter a number : ");
scanf("%d",&n);

int a=1;
for(int i=1;i<=n;i++){

for(int j=1;j<=i;j++){
int d=a+64;
printf("%c",d);

a++;}
printf("\n");
}


}






    
