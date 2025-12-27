# CPU Scheduling Algorithm Simulator

## Overview
This project is a **CPU Scheduling Algorithm Simulator** designed to visualize and compare
classic CPU scheduling strategies used in operating systems. The simulator allows users to
input process parameters and observe how different scheduling algorithms affect execution
order and performance metrics.

The goal of this project is to provide a clear, interactive way to understand scheduling
behavior, trade-offs, and fairness across algorithms.

---

## Algorithms Implemented
The simulator supports the following CPU scheduling algorithms:

- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- Shortest Remaining Time First (SRTF)
- Priority Scheduling
- Round Robin

Both **preemptive and non-preemptive** behaviors are handled where applicable.

---

## Features
- Interactive simulation of process scheduling
- Dynamic calculation of:
  - Waiting Time
  - Turnaround Time
  - Average Waiting Time
  - Average Turnaround Time
- Visualization of execution order using a Gantt-style timeline
- Comparison of algorithm performance under different arrival and burst time scenarios

---

## How It Works
1. Users provide process details such as arrival time, burst time, and priority.
2. The selected scheduling algorithm determines execution order.
3. The simulator computes scheduling metrics for each process.
4. Results are displayed visually to help analyze algorithm behavior and efficiency.

---

## Technologies Used
- Frontend: React, TypeScript
- Styling: Tailwind CSS
- Backend / Logic: Node.js
- Core Concepts: Operating Systems, Scheduling Algorithms

---

## Use Cases
- Understanding OS scheduling concepts
- Comparing algorithm efficiency and fairness
- Academic demonstrations and learning
- Interview preparation for operating systems topics

---


## Future Improvements
- Add support for multilevel queue scheduling
- Include context switch overhead in metrics
- Export simulation results
- Improve visualization for large process sets

---

## Conclusion
This project demonstrates the practical implementation of core operating system scheduling
algorithms and highlights the trade-offs between fairness, efficiency, and response time.
It serves as an educational tool to better understand how CPUs allocate execution time
among competing processes.
