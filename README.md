# Module-5 SEB
## AIM:
To write a program in C to print a string in reverse using a pointer.

## For example:

## program:
```c
#include<stdio.h>
#include<string.h>
int main(){
    char str[100];
    char *p;
    scanf("%[^\n]",str);
    p=str;
    int len=strlen(str);
    for(p=str+len-1;p>=str;p--){
        printf("%c",*p);
    }
    printf("\n");
    return 0;
}
```
## Result:
