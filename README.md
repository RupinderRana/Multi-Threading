# Multi-Threading
## Overview
This Python script benchmarks the performance of matrix multiplication using multi-threading. It generates 100 random matrices of size 1000x1000 and multiplies each of them with a constant matrix of the same size. The performance is measured for different numbers of threads ranging from 1 to 8.

## Prerequisites
1. Python 3.x
2. NumPy
3. Matplotlib
4. Pandas
The script will generate the following outputs: - Table showing the time taken for matrix multiplication with different numbers of threads. - Graph plotting the matrix multiplication time versus the number of threads. - CPU usages (if available). - Graph of CPU usage with percentage 0 to 100 percent

## Results Interpretation
Time Taken: Refers to the duration it takes to perform a specific operation or task. In this context, it represents the time taken to perform matrix multiplication.

## CPU Usage: 
Represents the percentage of CPU (Central Processing Unit) capacity utilized by the system at a given moment. It indicates how much of the CPU's processing power is being used.

## Number of Threads: 
Refers to the number of concurrent execution units within a process. In this code, it indicates the number of threads used for performing matrix multiplication in parallel. Increasing the number of threads can potentially improve performance by utilizing multiple CPU cores concurrently.

## CPU usage Graph
<img width="677" alt="cpu" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/dad11fae-e123-4629-9160-57522d8b4e48">

## CPU usage table
<img width="320" alt="cputable" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/748a2b8d-1868-4f61-8109-86db67d2c291">

## Time VS Threads
<img width="615" alt="time_thread" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/024383b7-135a-4ff5-ac4b-47feeafbdc56">

## Resultant Table
<img width="439" alt="rtable" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/919c190b-84af-4aee-b923-09cba59020b5">
