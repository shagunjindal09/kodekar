#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,k,sum;
    scanf("%d %d",&n,&k);
    if(n%2==0){
       sum=n/2;
    }
    else{
        sum=n/2+1;
    }
    printf("%d",sum*k);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
