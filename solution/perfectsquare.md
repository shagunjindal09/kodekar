#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,e,s;
    
    scanf("%d",&e);
    for(n=1;n<=e;n++){
        s=sqrt(n);
        s=s*s;
        
        if(s==n)
        {
            printf("%d ", n);
        }
            
        

    }
    
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
