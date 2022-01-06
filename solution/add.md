To manage the last digit of the amount kept in two accounts in a bank.
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int am1,am2,i,j;
    scanf("%d %d",&am1,&am2);
    i=am1%10;
    j=am2%10;
    if(i==j){
        printf("True");
    }
    else{
        printf("False");
    }

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
