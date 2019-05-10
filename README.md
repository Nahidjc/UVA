# UVA
#include<stdio.h>
int main()
{
    int t,n,m,i,total,result;
    scanf("%d",&t);
   while(t--)
    {
        scanf("%d %d",&n,&m);
        if( 6 <= n && m <= 10000)
        {
          total=(n/3)*(m/3);

        }
        printf("%d\n",total);
    }
}
