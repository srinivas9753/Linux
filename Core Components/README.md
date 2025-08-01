# Core Components of Linux

**Kernel**
The kernel is the heart of any Linux system, mediating between hardware and user applications. It handles process scheduling, memory management, and hardware abstraction. Loadable modules let you extend functionality without recompiling the entire kernel. Network stacks, file system drivers, and security mechanisms all reside here.
- Process management and scheduling
- Virtual memory and paging
- Device drivers and hardware interfaces
- Network protocol implementations

**Shell (Command Line Interface - CLI)**

🔹 A command interpreter that allows users to interact with the kernel.

🔹 Examples: Bash, Zsh, Fish, Dash, Ksh.

🔹 Converts user commands into system calls for the kernel.

**User Applications**

🔹 End-user programs like web browsers, text editors, DevOps tools, etc.

🔹 Applications interact with the OS using system calls via the shell or GUI.

