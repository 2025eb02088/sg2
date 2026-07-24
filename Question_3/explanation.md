# Question 3 Explanation

- `gcc -Wall -o file_utility file_utility.c`: This compiled the file utility program to make sure the system calls were implemented correctly.
- `./file_utility`: This created the employee database, wrote records, updated one record in place, and soft-deleted another.
- `od -A x -t x1z employees.db | head -10`: This inspected the binary file directly to confirm records were stored and updated at fixed offsets.
- `./file_utility | grep "Bob"`: This verified that Bob's updated salary appeared correctly in the program output.
- `./file_utility | grep "David"`: This confirmed that the deleted employee was no longer shown as active.
