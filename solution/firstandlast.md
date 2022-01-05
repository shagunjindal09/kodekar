#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,sum=0,first,last;
    scanf("%d",&n);
    last=n%10;
    while(n>=10){
        n=n/10;
       
    }
     first=n;
    sum=first+last;
    printf("%d",sum);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
