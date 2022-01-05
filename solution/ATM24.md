#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x;
    float y;
    scanf("%d",&x);
    scanf("%f",&y);
    if(x%5==0 && y>=(x+0.5)){
        y=y-x-0.5;
        printf("%.1f",y);
    }
    else{
        printf("%.1f",y);
    }

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
