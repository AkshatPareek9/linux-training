# Interview Questions for Linux

**Q 1. What happens when you run a linux command?**

    1. Shell listens the command
    2. It calls the fork() to create a child process
    3. child process calls execve() to load the program
    4. kernel schedules the run
    5. after completion, shell returns the output.


**Q 2. Process v/s thread**

    Process = Have it's own memory
    Thread = Shared memory inside the same process

**Q 3. Context Switching**

    CPU stops one process and load another process. Make the server performance slow.

**Q 4. Load Average**

    Number of process waiting + running

**Q 5. Page fault**

    When data not present in RAM and need to fetch from disk.

**Q 6. OOM Killer**

    Kills the process consuming most memory.

**Q 7. NUMA**

    Non uniform memory access : CPU uses its local memory for fast processing, as the remote memory is slow.
