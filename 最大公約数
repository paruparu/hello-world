//最大公約数の求め方

#include <stdio.h>

int main(void){
  int a,b,r,tmp;
puts("input two numbers");
scanf("%d%d",&a,&b);
//a>bになるように順番を変える
if(a<b){
  tmp=a;
  a=b;
  b=tmp;
}
//ユークリッド互除法
r=a%b;
while(r!=0){
  a=b;
  b=r;
  r=a%b;
}

  printf("The answer is %d\n",b);
}
