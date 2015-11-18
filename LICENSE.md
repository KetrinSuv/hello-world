#include <stdio.h>
#include <string.h>

int main()
{
  const char * msg = "Hello world!\n";
  int printf_res = printf(msg);
  if (printf_res < strlen(msg))
  {
    return 1;
  } else {
    return 0;
  }
}
