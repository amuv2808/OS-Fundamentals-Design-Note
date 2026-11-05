CPU Scheduling

Definition
CPU scheduling determines which process gets CPU time.

Scheduling Algorithms

1. FCFS
First Come First Serve executes processes in their arrival order.

2. SJF
Shortest Job First selects the process with the smallest CPU burst time.

3. SRTF
Shortest Remaining Time First is the preemptive version of SJF.

4. Priority Scheduling
The process with the highest priority is executed first.

5. Round Robin
Each process receives a fixed time quantum.

6. Multilevel Queue
Processes are divided into different scheduling queues.

7. Multilevel Feedback Queue
Processes can move between queues based on their execution behaviour.

Performance Measures
- CPU Utilization
- Throughput
- Waiting Time
- Turnaround Time
- Response Time

Example:
Consider three processes:
| Process | Burst Time |
| P1 | 5 |
| P2 | 3 |
| P3 | 1 |

Assume all processes arrive at time 0.

FCFS order: P1 → P2 → P3

Waiting times:
- P1 = 0
- P2 = 5
- P3 = 8

Average waiting time = (0 + 5 + 8) / 3 = 4.33 units.

SJF order: P3 → P2 → P1

Waiting times:
- P3 = 0
- P2 = 1
- P1 = 4

Average waiting time = (0 + 1 + 4) / 3 = 1.67 units.

Conclusion
CPU scheduling improves processor utilization and helps achieve efficient process execution.
