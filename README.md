#include <stdio.h>
#include<string.h>
int main()
{
   char str1[10] ="Vijay ";
   char str2[10] ="Vijay";
   char str3[10] ="vijay";
   printf("%d\n",strcmp(str1,str2));
   printf("%d\n",strcmp(str1,str3));
    return 0;
}
