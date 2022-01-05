include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,i,d,sum=0, inc=1;
    scanf("%d",&n);
    int div=n/2;
    for(i=1;i<=n;i++){
        for(int j=2;j<=i;j++)
        {
         if(i%j==0)
         {
             if(i==j)
             {
                 inc--;
             }
           inc++; 
             break;
         }
            
        }
       
    }
printf("%d",inc); 
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
