# MM
课程c
#include<stdio.h>
#include<string.h>
int main()
{
	printf("请输入一个句");
	char str[200];
	gets(str);
	printf("请输入一个词");
	char w[10];
	gets(w);
	strlwr(str);
	strlwr(w);
	int a=strlen(w);
	int b=strlen(str);
	int c=0;
	for(int i=0;i<=b-a;i++)
	{
		char tempw[a+1];
		
		for(int j=0;j<a;j++)  
		     tempw[j]=str[i+j];
		if(strcmp(tempw,w)==0) 
		          c++;

	}
	printf("%d",c);
	return 0;
}


