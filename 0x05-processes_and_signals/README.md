# 0x05 - Processes and Signals

This directory contains shell scripting exercises focused on process management and signal handling. These exercises teach how to inspect running programs, identify process IDs, and control processes using signals from the command line.

## Learning Objectives

- Identify and inspect running processes in Linux
- Use shell commands to find process IDs
- Understand process control with signals like `SIGTERM` and `SIGKILL`
- Write scripts that interact with and manage processes
- Practice graceful and forced termination of processes

## Exercises

- **0-what-is-my-pid**: Displays the current shell process ID
- **1-list_your_processes**: Lists the processes associated with the current user
- **2-show_your_bash_pid**: Shows the process ID of the current Bash session
- **3-show_your_bash_pid_made_easy**: Uses a simpler method to display the Bash PID
- **4-to_infinity_and_beyond**: Creates a process that runs indefinitely for signal testing
- **5-dont_stop_me_now**: Demonstrates sending a signal to stop or terminate a process
- **6-stop_me_if_you_can**: Starts a process that handles signals in a custom way
- **67-stop_me_if_you_can**: Additional or alternative signal-handling exercise
- **7-highlander**: Ensures only one instance of a script runs at a time
- **8-beheaded_process**: Sends termination signals to end a running process

## Key Concepts

### Process Management
- **PID**: Process ID for identifying a running program
- **PS**: Command to list active processes
- **PID inspection**: Finding and using process IDs from shell output

### Signals
- **SIGTERM**: Default signal to request graceful termination
- **SIGKILL**: Forceful termination signal that cannot be trapped
- **signal handling**: Making scripts respond to or ignore signals

## Usage

Each exercise file is executable. Run them individually to verify the behavior:

```bash
bash ./0-what-is-my-pid
bash ./1-list_your_processes
bash ./4-to_infinity_and_beyond
# ... and so on
```

## Prerequisites

- Basic shell scripting knowledge from earlier tasks
- Familiarity with Bash process and job control
- Understanding of shell variables, command substitution, and redirection

## Next Steps

After completing these exercises, you should be able to:
- Inspect and control processes from the shell
- Use signals to terminate or influence running programs
- Build scripts that manage process lifecycle and ensure only one instance runs
- Understand the practical differences between graceful and forced shutdown
