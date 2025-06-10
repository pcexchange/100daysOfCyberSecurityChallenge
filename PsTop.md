**PS AND TOP**

WHAT ARE PROCESSES AND WHY MONITOR THEM?

A process is a running program on your system. Eg like your terminal, a
web browser, or background services like cron. Monitoring processes is a
core cybersecurity skill because it helps you spot suspicious activity
eg malware, troubleshoot performance issues, or verify that tools are
running correcty. There are two powerful process commands : PS and TOP.

The PS: Process Status command gives a snapshot of running processes. It
consists of basic command lines such as:

- Ps: shows processes in my current terminal(eg bash and ps itself).

- Ps --u \$USER: lists all the processes under my user account.

- Ps aux: displays all system processes, including those owned by root
  or other users. This was eye-opening, showing systems lservices like
  system and VMwares vmtoolsd..

- Ps aux \| grep: this helps to find a specific service running in the
  background.

The TOP: this provides a live, interactive view of processes. Running
top showed :

- A system summary of CPU, memory and task counts etc.

- A list of processes with details like PID, user, CPU/memory usage and
  state.

Top also has few navigation keys such as pressing q to quit and k to
kill a process, top is ideal for ongoing monitoring

.![](media/image1.jpeg){width="2.379432414698163in"
height="1.723180227471566in"}![](media/image2.jpeg){width="2.51418416447944in"
height="1.74375in"}![](media/image3.jpeg){width="2.421986001749781in"
height="2.2866240157480315in"}![](media/image4.jpeg){width="2.4964534120734907in"
height="2.2715277777777776in"}
