# firstLinuxKernelModule

### attention: a bug in '#include <asm/uaccess.h>'
    You cannot include this file directly.
    Before include this file, you should also include '<linux/sched.h>'.

    The final pattern:
        #include <linux/sched.h>
        #include <asm/uaccess.h>