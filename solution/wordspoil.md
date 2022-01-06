#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char str[100];
    int i,j=1;
   fgets(str, sizeof str, stdin);
    for(i=0; str[i]!='\0';i++){
        if(str[i]==' ' || str[i]=='\n' || str[i]=='\t'){
            j++;
        }
    }
    printf("%d",j);
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
