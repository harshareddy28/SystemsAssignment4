# Instructions
## Compiling
- Firstly compile the program using ```gcc -Wall -o hw4 hw4.c -pthread ```
## Execution
- To execute the program, run `./output {max_threads_allowed}`, for example, ```./hw4 3```
- Once the program is running the following commands cane be inputted: `showjobs`, `submithistory`, `submit`
- Submit - `submit {path_to_executable}`, for example, `submit /home/user/fibonacci`. This command creates a new job and this job executes the given executable, in the above example's case it's fibonacci program.
- Showjobs - `showjobs` shows the list of jobs in the queue which are waiting to be executed.
- showhistory - `showhistory` command displays all the jobs that have executed.

Once after doing this, come out of it and check the files using ls command. You'll be able to see all the files in the directory. Use 2_out.txt to see the output of the files that we have submitted and that's all

