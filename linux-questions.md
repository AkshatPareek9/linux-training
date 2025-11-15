# Interview Questions for Linux

**Q 1. What happens when you run a linux command?**

    1. Shell listens the command
    2. It calls the fork() to create a child process
    3. child process calls execve() to load the program
    4. kernel schedules the run
    5. after completion, shell returns the output.

---
