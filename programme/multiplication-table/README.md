## Write a program to output the following multiplication table.

```
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
...
5 x 10 = 50
```

---

<CodeBlock slots="heading, code" repeat="1" languages="C" />

#### C

```c
#include <stdio.h>

void main()
{
    int n = 5;
    for(int i=1; i<=10; i++) {
        printf("%d x %d = %d\n", n, i, n*i);
    }
}
```
