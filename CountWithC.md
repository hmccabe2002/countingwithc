# Counting in `C`
### [For Loop](forloopcount.c "For Loop")
```C
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    int x, i;
    printf("What number do you want to count to? ");
    scanf("%d", &x);
    for (i = 1; i <= x; i++)
    {
        printf("%d ", i);
    }
    printf("\n");
    return 0;
}
```
### [While Loop](whileloopcount.c "While Loop")
```C
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    int x, i;
    printf("What number do you want to count to? ");
    scanf("%d", &x);
    i = 1;
    while (i <= x)
    {
        printf("%d ", i);
        i++;
    }
    printf("\n");
    return 0;
}
```
***
<hmc@programmer.net>
