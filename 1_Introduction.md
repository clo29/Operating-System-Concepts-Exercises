# Introduction

### 1.1
The three main purposes are:
- To provide an interface to abstract the hardware for computer user to use computer.
> in a convenient and efficient way.
- To allocate and manage computer resources such as memory, mutex, etc., for user and kernel programs.
- To communicate and control with peripheral devices by I/O control like mouse, keyboard etc.
> Supervision of the execution of user programs to prevent errors and improper use.

### 1.2
A good example is GUI, it definitely wastes more resources than pure command line interface, but GUI can make better user experience and more convenient in some situations.


### 1.3
The main difficulty of writing a real-time operating system is tasks in real-time environment must be done within a period of time constraint, otherwise the system will fail and shutdown or even crash.

### 1.4
- It SHOULD include: Web browsers and mail programs can take advantage of features in operatinh system kernel and get better performance.
- It SHOULD NOT include: Web browsers and mail programs are kind of user programs, if we include them into operating system, it could be harder to maintain because they might be able to access kernel features directly, and the potentail security problem might also become severer because web browsers and mail programs are good targets for hackers or malware.
> Applications are applications, not part of an operating system.
> Inclusion of applications leads to a bloated operating systems.

### 1.5
Instructions can be classified to two types: Only can be executed in kernel mode and can be executed in both modes. Computers should resstrict some important instructions, such as which can change mode to kernel mode, access to hardware, allocate/free resources to kernel mode only to protect critical resources.

### 1.6
- a. Priviledged.
- b. Non-priviledged.
- c. Priviledged.
- d. Non-priviledged.
- e. Priviledged.
- f. Priviledged.
- g. Priviledged.
- h. Priviledged.
