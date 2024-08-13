# CPU-Scheduling-Simulation

This C-based CPU scheduling simulation implements a Multilevel Feedback Queue using three distinct queues, incorporating both the Round Robin (RR) and First Come First Serve (FCFS) algorithms.

## Implementation:

### Multilevel Feedback Queue:

Queue 1: Round Robin (RR) with a quantum of 8.
Queue 2: Round Robin (RR) with a quantum of 16.
Queue 3: First Come First Serve (FCFS).

### CPU Allocation:
The CPU allocates 50% of its time to Queue 1.
The CPU allocates 30% of its time to Queue 2.
The CPU allocates 20% of its time to Queue 3.

### Promotion and Demotion: 
Processes are promoted or demoted between queues based on a 50% random chance.

### Assumption: 
The CPU time is set to 160 units, chosen so that 50% of it is a multiple of 8 and 30% is a multiple of 16.

### Process Generation: 
The simulation generates 100 random processes, each with a unique ID and burst time.
