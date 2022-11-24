# ucos-ii_EDF

## What is EDF?

Earliest deadline first (EDF) is an optimal dynamic priority scheduling algorithm mainly used in real-time operating systems. It can be described through the following points:

- Priority driven: Each process is assigned a priority and the scheduler selects the process to run according to it. Hence, the process with the highest priority is carried out first. In the case of EDF, the priority is set according to the absolute deadline of each process.

- Dynamic: Priorities are calculated and can change while the processes are running; unlike static scheduling, in which the priorities are already assigned before the processes are being carried out.

- Executes in preemptive mode: This means that time slots of the CPU can be divided for a process. In other words, it is not required that the same process holds the resource given to it throughout its life cycle. Instead, it can be interrupted by another process if that other process has a higher priority. EDF also runs on non-preemptive uniprocessors, but it does not allow inserted idle time.

## Result

- Task input file (ucos-ii__EDF\Microsoft\Windows\Kernel\OS2\VS\TaskSet.txt)
![](https://i.imgur.com/dSjgGP5.png)

- Scheduling diagram
![](https://i.imgur.com/3Jd77jB.png)

- Final result
![](https://i.imgur.com/pGIHCgB.png)