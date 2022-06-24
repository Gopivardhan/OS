<h1 align='center'>Fork() concept examples</h1>

<h2>Example 1</h2>

```c
#include <sys/types.h>

#include <studio.h>

#include <unistd.h>

int main()

{

processID pid;

/* create a process */

pid = fork();

if (pid < 0) /* error occurred */

fprintf(stderr, “ERROR");

else if (pid == 0) /* child process */

execlp("/bin/ls", "ls", NULL);

else /* parent process */

/* parent waits for the child to complete */

wait (NULL);

printf ("Child Complete");

}
```
