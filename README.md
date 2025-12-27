# Job Shop Scheduling Problem
This project focuses on solving the **Job Shop Scheduling Problem (JSSP)** - a classic production planning and scheduling problem. In JSSP, multiple jobs consist of ordered sequences of operations. Each operation must be processed on a specific machine for a given duration. The goal is to build an optimal schedule that minimizes the total completion time makespan.


## Problem Definition

- A set of **Jobs**
- Each job consists of ordered **Operations**
- Each operation is processed on a **Machine (Work Center)** for a fixed time

## Constraints

- **Precedence constraints**: operations within a job must follow a strict order
- **Machine capacity constraints**: a machine can process only one operation at a time
- **Non-preemption**: once started, an operation must run to completion

## Objectives

- Minimize total completion time (**makespan**)
- Meet job deadlines
- Reduce delays and machine idle time
- Prioritize urgent jobs
- Select the optimal machine for each operation (**Flexible JSSP — FJSSP**)

## JSSP vs FJSSP

- **JSSP**: each operation is assigned to a fixed machine
- **FJSSP**: each operation can be processed on one of several machines, and the optimizer selects the best assignment to minimize makespan or delays
