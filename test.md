# > Free

This command will give you the amount of memory free on your system. The second line of this command gives you the actual free memory. This is because it subtracts cache memory.


In linux cache memory is considered as free memory as it is available on demand for your applications to use.


### Show Memory in kb (KiloByte)
    free

###   Show Memory in mb (MegaByte)
    free -m

### Show Memory in gb (GigaByte) or Human Readable

    free -h


### Swap

The "Swap" section displays information about the swap space on the server. Swap space is used when the system runs out of physical memory and needs to store some data on the hard drive temporarily.


# > Htop

htop is a system monitor and process viewer for Unix-based systems that provides an interactive interface for monitoring system resources and managing processes. It is an advanced alternative to the traditional "top" command, offering a more user-friendly and feature-rich experience.

### -d seconds: Specifies the delay between screen updates, in seconds.

    htop -d

### -u user: Only displays processes for a specific user.

    htop -u <username>

### -p PID: Only displays a specific process with the given process ID (PID).

    htop -p 12368

### -C: Turns off color output.

    htop -C

### -t: Displays tree view, showing the relationship between processes.

    htop -t

### -s: Sorts the process list

htop -s


# > Top

Displays real-time system resource usage, including CPU and memory usage.

### top -d delay: Specifies the delay between screen updates, in seconds.
    top -d 2

### top -b: Runs top in batch mode, where the output is suitable for parsing by other programs.
    top -b

### top -c: Enables or disables the display of the command line for each process.
    top -c

### top -p pid: Only displays a specific process with the given process ID (PID).
    top -p

### top -u user: Only displays processes for a specific user.
    top -u root


# > Vmstat
Displays virtual memory statistics, including CPU, memory, and I/O usage.

vmstat: Displays the virtual memory statistics for the system in a standard format.
vmstat -a: Displays active and inactive memory, swap space, paging space, and I/O statistics for all devices.
vmstat -d: Displays disk I/O statistics for all devices.
vmstat -f: Displays the number of forks since boot time.
vmstat -m: Displays detailed virtual memory statistics for the system.
vmstat -n: Disables the display of the header information in the output.
vmstat -s: Displays virtual memory statistics for the system in a more detailed format.
vmstat -t: Enables or disables the display of timestamps for each row of output.
vmstat -z: Displays statistics on memory usage by zone.
These options can be used to display different types of virtual memory statistics, and to control the format and level of detail of the output. They can help users to identify potential performance issues related to CPU, memory, or I/O usage, and to optimize system configuration for better performance.

# > dmesg
 Displays kernel ring buffer messages, including system events, errors, and warnings.

dmesg: Displays the entire kernel ring buffer, including all messages from boot time until the present.
dmesg -c: Clears the kernel ring buffer after displaying its contents.
dmesg -D: Enables or disables the display of timestamp information in the output.
dmesg -d: Enables or disables the display of kernel message levels (debug, info, warning, error).
dmesg -E: Enables or disables the display of human-readable error messages.
dmesg -H: Enables or disables the display of human-readable messages for each log level.
dmesg -n level: Sets the minimum message level to be displayed, where level can be debug, info, notice, warning, err, crit, alert, or emerg.
dmesg -T: Enables or disables the display of human-readable timestamps.
dmesg -w: Enables or disables the continuous printing of new kernel messages as they arrive.


# > uptime

The uptime command is used to display the current system uptime, as well as the system load average over a certain period of time. 

uptime: Displays the current system time, the system uptime, and the load average over the last 1, 5, and 15 minutes.
uptime -p: Displays the system uptime in a more human-readable format.
uptime -s: Displays the date and time when the system was last started.
uptime -V: Displays the version information for the uptime command.
These options can be used to display the system uptime and load average in different formats, as well as to retrieve additional information about system performance and behavior. They can help users to monitor system performance, diagnose performance issues, and plan maintenance and upgrades.



