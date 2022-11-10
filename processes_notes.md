Processes store their information in /proc

# Listing processes with ps

Process states (+ as fg)

VSZ: mem allocated for the process

RSS: actually mem used by the process. Represents physical mem that cannot be swapped.

# Using top command

Press h to see help options, and then press any key to return to the top display.

Press M to sort by memory usage instead of CPU, and then press P to return to sorting by CPU.

Press the number 1 to toggle showing CPU usage of all your CPUs if you have more than one CPU on your system.

Press R to reverse sort your output.

Press u and enter a username to display processes only for a particular user.

# Managing Background and Foreground processes

## Starting background process

$ cmd &

## Using foreground and background commands

$ fg %[pid]

# Managing processes with cgroups