### Basic c programming code
```
#include <stdio.h>
int main()
{
    printf("Hello World");
}
```


### Basic c programming code
```
#include <stdio.h>
int main()
{
    int NumOne;
    printf("Enter a number: ");
    scanf("%d", &NumOne);

    printf("The Number you have Entered = %d\n", NumOne);
}
```

### Sum of 2 inegers
```
#include <stdio.h>
int main()
{
    int NumOne, NumTwo, sum;
    printf("Enter 1st Number: ");
    scanf("%d", &NumOne);

    printf("Enter 2nd Number: ");
    scanf("%d", &NumTwo);

    sum= NumOne+ NumTwo;

    printf("Sum  = %d\n", sum);
}
```