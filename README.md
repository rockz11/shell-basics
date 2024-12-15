#shell-basics
# grep is used to find the data or some phrases in specified file.
who | sort
who | wc -l 
What is process?
A process is a unit for provisioning for system 
resources.
It is any program ,application, or command that runs on the system.
A process is created in memory location in its own address space 
when a application,or program,or command is intiated.
we us command : ps
Process are organized hierarchial fashion.Each process.has parent process. Also Known as calling process.
A single parent process has may have one or more child process
Each process has assigned a unique identification number.
That is known as PID (process identifier).
Several process are spawned at boot system.many sits at memrory to wait 
for an event to trigger to request to use their services. These background systems process are called daemons are critical to system operablity.
command: which ps
command: ps # shows the process which are in terminal.
command: which top  # to view real time process.
command: ps -a , ps -e ,ps -f , ps -l
