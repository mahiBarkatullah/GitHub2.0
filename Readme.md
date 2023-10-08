### Basic c programming code
```
#include <stdio.h>
int main()
{
    printf("Hello World");
}
```


### Basic user input
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

## Colloboration Project
---
#### Master Branch
```
#include <stdio.h>
int main()
{
    int NumOne, NumTwo, sum, sub, mult, div, rem;
    scanf("%d", &NumOne);
    scanf("%d", &NumTwo);

    sum = NumOne+ NumTwo;
    sum = NumOne- NumTwo;
    mult = NumOne*NumTwo;
    div = NumOne/NumTwo;
    rem = NumOne%NumTwo;
    printf("%d\n", sum);
    printf("%d\n", sub);
    printf("%d\n", mult);
    printf("%d\n", div);
    printf("%d\n", rem);
}

```


#### Prompt Branch
```
#include <stdio.h>
int main()
{
    int NumOne, NumTwo, sum, sub, mult, div, rem;
    printf("Enter 1st Number: ");
    scanf("%d", &NumOne);
    printf("Enter 2nd Number: ");
    scanf("%d", &NumTwo);

    sum = NumOne+ NumTwo;
    sum = NumOne- NumTwo;
    mult = NumOne*NumTwo;
    div = NumOne/NumTwo;
    rem = NumOne%NumTwo;
    printf("Sum = %d\n", sum);
    printf("Sub = %d\n", sub);
    printf("Multiplication = %d\n", mult);
    printf("Divisor = %d\n", div);
    printf("Remainder = %d\n", rem);
}

```