# test
学习c写的代码
#include<stdio.h>
int main()
{
	int a=0;
	scanf("%d",&a);
	int b=a%2;
	if(b==1)
	printf("%d是奇数",a);
	else
	printf("%d是偶数",a); 
	
	
	
	
	return 0;
 } 
 #include<stdio.h>//代码不行 达不到效果 下面用for语句 
 int main()
 {
 	int i=0;
 	int a=i%2;
 	while(i<=100)
 {
 	if(a==1)
 	printf("%d\n",i);
 	else
 	i++;
 	
 	
 }
 
 	return 0;
  } 
  
  
  
  #include<stdio.h>
  int main()
  {
  	int i;
  	
  	for( i=1;i<=100;i++)
  	{
  		if(i%2==1)
  		printf("%d\n",i);
	  }
  	
  	
  	
  	
  	
  	
  	return 0;
  }
 
  
  #include<stdio.h>
  int main()
  {
  	int i=1;
  	 
  	while(i<=100)//while 前面一句应该只能和表达式有关  不能把int b=a%2 放在while 外面 
  	{
  		 int b=i%2;
  		if(b==1)
  		printf("%d\n",i);
  		i+=1;//或者用i++ 
  		
  		
  		
	  } 
  	
 	
  	
  	
  	
  	
  	return 0;
  }
  
  
  
  //另一种简单的方法 规律法 创建等差数列 
  
  #include<stdio.h> 
  int main()
  {
  	int i=1;
  	while(i<101)
  {
  	
  	printf("%d",i);
  	i+=2;
  	
  	
  }
  	
  	
  	
  	
  	
  	
  	
  	return 0;
  }
  
  
