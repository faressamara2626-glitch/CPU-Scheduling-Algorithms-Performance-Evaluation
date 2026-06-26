# CPU Scheduling Algorithms Performance Evaluation

## Overview
This project is an Operating Systems project focused on evaluating and comparing different CPU scheduling algorithms. The goal is to understand how each scheduling method affects waiting time, turnaround time, fairness, responsiveness, and system performance.

## Project Topic
Performance Evaluation of CPU Scheduling Algorithms

## Algorithms Covered
The project evaluates the following CPU scheduling algorithms:

- First-Come, First-Served (FCFS)
- Round Robin (RR)
- Shortest Remaining Time First (SRTF)
- Non-Preemptive Priority Scheduling (PS-NP)
- Shortest Job First (SJF)

## My Contribution
My assigned part in this project was:

- Shortest Job First (SJF)

## SJF Summary
Shortest Job First is a non-preemptive CPU scheduling algorithm. The CPU selects the process with the smallest burst time among the processes that have already arrived. Once a process starts executing, it continues until completion.

## Evaluation Metrics
The project evaluates each algorithm using:

- Completion Time
- Waiting Time
- Turnaround Time
- Average Waiting Time
- Average Turnaround Time

## Results Summary
The project compares algorithms based on their average waiting time and average turnaround time.

| Algorithm | Average Waiting Time | Average Turnaround Time |
|---|---:|---:|
| FCFS | 9.00 | 15.50 |
| Round Robin | 11.75 | 18.25 |
| SRTF | 5.75 | 12.25 |
| Priority Scheduling Non-Preemptive | 7.75 | 14.25 |
| SJF | 7.25 | 13.75 |

## Key Insights
- FCFS is simple but can suffer from the convoy effect.
- Round Robin provides fairness and is suitable for time-sharing systems.
- SRTF gives the lowest average waiting time in this example but may cause starvation.
- Priority Scheduling is useful when task importance matters, but low-priority tasks may starve.
- SJF performs well among non-preemptive algorithms by reducing average waiting and turnaround time.

## Files in This Repository
```text
CPU-Scheduling-Algorithms-Performance-Evaluation/
│
├── OS_project.docx
└── README.md
