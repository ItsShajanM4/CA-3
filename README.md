# CA-3
Assignment 3

The printNumbers file contains C programming language code to print numbers from 2 to 11. It initally printed numbers from 1 to 10 however, we changed it so that it printed numbers 2 to 11 instead.

To run the code you can copy and paste in an online IDE that runs c programming language or use an IDE software.

**Initial Code**
// Print numbers from 1 to 10
#include <stdio.h>

int main() {
  int i;

  for (i = 1; i < 11; ++i)
  {
    printf("%d ", i);
  }
  return 0;
}


**New Code**
// Print numbers from 2 to 11
#include <stdio.h>

int main() {
  int i;

  for (i = 1; i < 11; ++i)
  {
    printf("%d ", i+1); // added +1 next to i
  }
  return 0;
}
