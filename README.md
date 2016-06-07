# Usage

    #include "syscall_x64.h"
    
    main(){
        printf("%s\n", __syscall_x64[2]);
        // prints "open", as the system call number of open is 2
    }
