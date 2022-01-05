#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char s[70];
    int i,len,temp=0;
    
    gets(s);
    len=strlen(s);
    for(i=1;i<len;i++){
        if(s[i]!=s[len-i-1]){
            temp=1;
        break;
        }
            
    }
    if(temp==0){
        printf("1");
    }
    else{
        printf("0");
    }
    
    

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
