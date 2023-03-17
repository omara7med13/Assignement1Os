# Assignement1Os

![My Image](Screenshot (149).png)
## SJF
 the shortest job first algorithm is an algorithm which executes the process whose burst time is least and has arrived before the current time. Therefore, in order to find the process which needs to be executed, sort all the processes from the given set of processes according to their arrival time. This ensures that the process with the shortest burst time which has arrived first is executed first
 <a href="
After selecting a process which needs to be executed turn around time and waiting time is calculated by using arrival time and burst time of the process
Completion Time = Start Time + Burst Time
Turn Around Time = Completion Time – Arrival Time
Waiting Time = Turn Around Time – Burst Time


![My Image](Screenshot (150).png)
## ROUNDROBIN
Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way. It is basically the preemptive version of First come First Serve CPU Scheduling algorithm.
A fixed time is allotted to each process, called a quantum, for execution.

Once a process is executed for the given time period that process is preempted and another process executes for the given time period.
Turn Around Time This mainly indicates the time Difference between completion time and arrival time. Turn Around Time = Completion Time – Arrival Time

Waiting Time(W.T): It Indicates the time Difference between turn around time and burst time. Waiting Time = Turn Around Time – Burst Time
