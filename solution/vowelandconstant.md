#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int l,v=0,c=0;
    char str[20];
    gets(str);
    int ln=sizeof(str);
    for(int j=0;j<ln;j++){
       if(str[j])
           { ++l;}
        else
        {
            break;}
    }

    for(int i=0;i<l;i++){
        if(str[i]=='a'||str[i]=='e'||str[i]=='i'||str[i]=='o'||str[i]=='u')
            v++;
        else
            c++;
    }
    printf("%d %d",v,c);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
