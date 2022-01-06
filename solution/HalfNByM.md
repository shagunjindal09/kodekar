#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y,i,z;
    scanf("%d %d",&x,&y);
    for(i=1;i<y;i++){
        z=x/2;
        x=z;
    }
    printf("%d",x);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
