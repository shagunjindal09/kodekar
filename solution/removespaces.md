#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    char s[100];
    int i=0,j, len;
    gets(s);
    
    len = strlen(s);
    for(i=0; i<len; i++)
    {
        if(s[0]==' ')
        {
            for(i=0; i<(len-1); i++)
            {
                s[i] = s[i+1];
            }
            s[i] = '\0';
            len--;
            i = -1;
            continue;
            
        }
        if(s[i]==' ' && s[i+1]==' ')
        {
            for(j=i; j<(len-1); j++)
            {
                s[j] = s[j+1];
            }
            s[j] = '\0';
            len--;
            i--;
        }
    }
    printf("%s", s);
    
    
    

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
