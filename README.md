# RR AND SJF SCHEDULING ALGO IMPLEMENT IN JAVA CODE
A Process Scheduler schedules different processes to be assigned to the CPU based on particular scheduling algorithms. There are six popular process scheduling algorithms which we are going to discuss in this chapter −
First-Come, First-Served (FCFS) Scheduling
Shortest-Job-Next (SJN) Scheduling
Priority Scheduling
Shortest Remaining Time
Round Robin(RR) Scheduling
Multiple-Level Queues Scheduling


## Shortest Job Next (SJN)
This is also known as shortest job first, or SJF
This is a non-preemptive, pre-emptive scheduling algorithm.
Best approach to minimize waiting time.
Easy to implement in Batch systems where required CPU time is known in advance.
Impossible to implement in interactive systems where required CPU time is not known.
The processer should know in advance how much time process will take.
 
 ![My Image](https://github.com/johhnngeo/rr-and-sjf/blob/main/Screenshot%202023-03-17%20230924.png)
  
## Round Robin Scheduling
Round Robin is the preemptive process scheduling algorithm.
Each process is provided a fix time to execute, it is called a quantum.
Once a process is executed for a given time period, it is preempted and other process executes for a given time period.
Context switching is used to save states of preempted processes.
