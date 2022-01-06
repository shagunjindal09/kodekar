#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
int n,z,f,g;
    scanf("%d",&n);
    if(n>=1 && n<=10){
      z=  n+n;
       f= z+n;
       g= f/2;
       printf("%d",g-n);
    }
    
    
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
