#include <stdio.h>
#include <string.h>

int main(){
char str[100];
printf("Enter a string:\n",);
scanf("%s", str);
printf("Length= %zu \n", strlen(str));
return 0;
}
