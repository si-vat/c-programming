#include<stdio.h>
int main()
{
	int p,q,r;
	char ch ;
	do
	{
	
		printf("P=");
		scanf("%d",&p);
		printf("Q=");
		scanf("%d",&q);
		printf("R=");
		scanf("%d",&r);
		for(int i=p;i<=q;i++)
		{
			int j=i/10;
			int x=i/100;
			if(i%10==r || j%10==r || x%100==r)
			{
				continue;
			}
			else
			{
				printf("%d\n",i);
						
			}
		}
		printf("do you want to continue(1/0):");
		scanf("%c",&ch);
	
	}while(ch=='y');
}
