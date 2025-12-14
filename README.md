# Energy Efficient CPU Scheduling Algorithm

## Project Overview
This project is developed as part of the Operating Systems course.
The goal is to compare traditional CPU scheduling algorithms with an
energy-efficient scheduling approach.

The project simulates CPU scheduling using:
- FCFS
- SJF (Non-Preemptive)
- SRTF (Preemptive)
- Priority (Preemptive & Non-Preemptive)
- Round Robin
- Energy Efficient Scheduling Algorithm

The energy-efficient algorithm reduces power usage using:
- Shortest Job First strategy
- Reduced context switches
- Dynamic Voltage and Frequency Scaling (DVFS)
- CPU Sleep Mode during idle time

---

## Features
- Calculates Waiting Time and Turnaround Time
- Computes Energy Consumption
- Displays Gantt Chart
- Shows number of context switches
- Compares traditional and energy-efficient scheduling

---

## Technologies Used
- Language: C++
- Platform: GitHub
- Concepts: CPU Scheduling, Energy Optimization, DVFS

---

## How to Run
Compile and run using any C++ compiler:

```bash
g++ cpu_scheduling.cpp -o run
./run
