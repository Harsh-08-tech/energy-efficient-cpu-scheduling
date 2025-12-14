# Energy Efficient CPU Scheduling Algorithm

## Course
Operating Systems (CSE316)

## Project Topic
Energy Efficient CPU Scheduling Algorithm

## Problem Statement
Traditional CPU scheduling algorithms focus mainly on performance metrics like
waiting time and turnaround time. However, modern systems (especially mobile and
embedded devices) require energy-efficient scheduling to reduce power consumption.

This project implements and compares classical CPU scheduling algorithms with an
Energy-Efficient CPU Scheduling Algorithm that reduces energy usage using:
- Shortest Job First strategy
- Dynamic Voltage and Frequency Scaling (DVFS)
- Reduced context switches
- CPU idle/sleep power handling

---

## Algorithms Implemented
- First Come First Serve (FCFS)
- Shortest Job First (Non-preemptive)
- Shortest Remaining Time First (Preemptive)
- Priority Scheduling (Preemptive & Non-preemptive)
- Round Robin
- **Energy Efficient CPU Scheduling Algorithm (SJF + DVFS + Sleep Mode)**

---

## Energy Efficient Algorithm Highlights
- Executes shorter jobs first to finish processes earlier
- Uses ECO mode (low power) for short jobs
- Uses HIGH mode only when required
- Reduces unnecessary context switches
- Puts CPU into sleep mode during idle time

---

## Metrics Calculated
- Completion Time
- Turnaround Time
- Waiting Time
- Energy Consumption
- Context Switch Count
- Gantt Chart visualization

---

## Technologies Used
- Language: C++
- Version Control: GitHub

---

## How to Run
Compile and run the C++ file:

g++ cpu_scheduling.cpp -o run
./run


---

## Branch Note
Energy optimization improvements implemented in separate branch.

## Conclusion
The Energy Efficient CPU Scheduling Algorithm consumes less energy compared to
traditional scheduling algorithms while maintaining acceptable performance,
making it suitable for power-constrained systems.
