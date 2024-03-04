---
permalink: /posts/PC

---

# Record of playing on PWN College

## Lifecycle of Sec
![life](/assets/images/sec_cycle.png)

# Tips

## Seccomp
Kernel escape sccomp cannot pass to child process, 
so don't use exec syscall to read the flag.

## python: global interpreter lock
Python cannot have true parrallelism using multithreading.

A mechanism used in computer-language interpreters
to synchronize the execution of threads 
so that only one native thread (per process) can execute at a time.
Therefore, fork() must be used in exploitation.