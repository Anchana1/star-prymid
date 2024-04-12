# star-prymid
----------------------c program-----------------------------------------------------------
#include <stdio.h>
int main()
{
   int r = 8, i, j, space;
 
   for (i = r; i >= 1; --i) 
   {
       for (space = 0; 
            space < r - i; ++space)
           printf("  ");
       for (j = i; j <= 2 * i - 1; ++j)
           printf("* ");
       for (j = 0; j < i - 1; ++j)
           printf("* ");
       printf("\n");
   }
   return 0;
}
output:
* * * * * * * * * * * * * * * 
  * * * * * * * * * * * * * 
    * * * * * * * * * * * 
      * * * * * * * * * 
        * * * * * * * 
          * * * * * 
            * * * 
              * 
