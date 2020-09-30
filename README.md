#include<stdio.h>
int main() 
{
char str[]="Ibqqz!Ipmj!Tjs!Kj",*p;
p=str;
while(*p!='\0')
--*p++;
printf("%s",str);
return '0';
}
