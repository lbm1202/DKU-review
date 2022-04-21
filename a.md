# 0904 basic programming

> Hello World!

```c
#include <stdio.h>

int main(void){ //main function , starting point
  printf("Hello, World\n");
  return 0;
}
```

> Main Function

- every c program has "main" function.
- Every c program start "main" function.

---

> Function in C

- "main" function returns 0.
- Each statement ends ' ; '.

---

> printf function

- Standard library <stdio.h>

- Escape sequences

- <pre>
  \n : new line
  \r : Carriage Return
  \t : Horizontal Tab
  \\ : Backslash
  \' : Single quotation mark
  \" : Double quotation mark
  </pre>

---

```c
#include <stdio.h>

int main(void){
  printf("Hello, World\n");
  printf("Hello, Universe\n");
  return 0;
}
```

> Same as

```c
#include <stdio.h>

int main(void){
  printf("Hello, World\nHello, Universe\n");
  return 0;
}
```

---

> Compile

1. Editor
   - Write Code
2. Compile
   - Basic syntax check
3. Link
   - Check the function exist
4. Execute
   - .exe

---

> Process

1. Editor
2. HDD
3. RAM
4. CPU

**Why computer use RAM** —>> HDD is slow , RAM is fast

---

## Coding Style

```c
#include <stdio.h>

int main(void){ 
  printf("Hello, World\n");
  return 0;
}
```

> Same as

```c
#include <stdio.h>
int main(void){printf("Hello, World\n");return 0;}
```

> But readability is bed



