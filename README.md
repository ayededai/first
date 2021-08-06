# first
#include<stdio.h>//冒泡排序
int main()
{
   int a[10],i,j,t;
    for(i=0;i<sizeof(a)/sizeof(a[0]);i++)
    {
       scanf("%d",&a[i]);
    }
    for(i=0;i<sizeof(a)/sizeof(a[0])-1;i++)
     {
        for(j=0;j<sizeof(a)/sizeof(a[0])-i-1;j++)
          {
            if(a[j]>a[j+1])
            {
              t=a[j];
              a[j]=a[j+1];
              a[j+1]=t;
            }
          }
     }
  return 0;
}

