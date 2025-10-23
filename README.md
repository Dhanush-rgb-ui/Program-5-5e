# Module-5 SEB
## AIM:
To write a program in C to print a string in reverse using a pointer.

## For example:
<img width="477" height="70" alt="image" src="https://github.com/user-attachments/assets/1827cd9b-86ec-4a37-a364-394e98674568" />

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
<img width="805" height="112" alt="image" src="https://github.com/user-attachments/assets/bdf1b837-dd66-40da-8d97-daec636d8385" />
