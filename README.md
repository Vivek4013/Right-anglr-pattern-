# Right-anglr-pattern-
#include <stdio.h>
#include<conio.h>
void main()
int i,j,row;
clrscr;
printf("enter the number of row");
scanf("%d",rows);
for(i=0; i<rows;i++)
{
for(j=1;j<=rows-i;j++)
{
printf("%d",j);
}
printf("\n");
}
getch();
}
