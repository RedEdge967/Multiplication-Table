# Multiplication-Table
- This program show the multiplication table of any number up to a any number you choose.

## Needed
- A program to run C files
- Or a online c compiler

## How to?
- Download the release in [here](https://github.com/RedEdge967/Multiplication-Table/releases) and run it.
- or copy the code below and paste it on a online compiler and run it.
```c
#include <stdio.h>
int main() {

  int n, i, range;
  printf("Enter an integer: ");
  scanf("%d", &n);

  // prompt user for positive range
  do {
    printf("Enter the range (positive integer): ");
    scanf("%d", &range);
  } while (range <= 0);

  for (i = 1; i <= range; ++i) {
    printf("%d * %d = %d \n", n, i, n * i);
  }

  return 0;
}
```
> Remember to give a star :star2: if you used this and got it as useful.
