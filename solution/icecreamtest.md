#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,v=250,c=320,s=120,m;
    int left ,sum;
    scanf("%d",&n);
      
      left=n-v;
       sum=c+s;
    if(left>sum)
    {
        m=left-sum;
        printf("%d %d",1,m);
    }
    else{
        printf("0");
    }

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
