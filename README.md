#include <stdio.h>
#include <stdlib.h>

int main()
{
    int text1,text2;
    char i;
    printf("please input the formula:");
    scanf ("%d%c%d",&text1, &i, &text2);
    switch (i)
    {
         case'+':
             printf("%d + %d= %d\n",text1+text2);
             break;
         case'-':
             printf("%d - %d= %d\n",text1-text2);
             break;
         case'*':
             printf("%d * %d= %d\n",text1*text2);
             break;
         case'/':
             printf("%d / %d= %d\n",text1/text2);
             break;

    }
return 0;
}
