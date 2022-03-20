# MM
课程c
#include<stdio.h>
#include<string.h>
int main()
{
  char str[456]; 
  char b;
  int number=0;
  int i=0;
  printf("请输入句子");
  gets(str)	;
  strlwr(str);
  printf("请输入句子中某个单词");
  scanf("%c",&b);
  for(i;i<=456;i++)
  {
  	if(b==str[i])
  	{
	    number++;
    }
  }
  printf("%d",number);
  return 0;
}

