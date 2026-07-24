# Question 2 Explanation

- `gcc -o process_monitor process_monitor.c`: This compiled the C program so the process monitor could be tested.
- `./process_monitor`: This executed the monitor to create child processes, observe their states, and verify that zombies were reaped.
- `gcc -Wall -o process_monitor process_monitor.c 2>&1`: This recompiled the program with warnings enabled and captured compiler output for validation.
