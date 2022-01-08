
int main()
{
    int num,i,last,sum,cur,j;
    long long int fact;
    printf("enter the number");
    scanf("%d",&num);
    for(i=1;i<=num;i++){
      cur=i;
      sum=0;
      while(cur>0){
          fact=1;
          last=cur%10;
          for(j=1;j<=last;j++){
              fact=fact*j;
          }
          sum+=fact;
          cur/=10;
      }
      if(sum==i){
          printf("%d ",i);
      }
    }

    return 0;
}
