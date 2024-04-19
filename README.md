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

## CPU usage 
<img width="685" alt="cpu_bar" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/643daee4-b8b0-4c0b-a95c-ae4cfefa13bf">

## CPU usage table
<img width="512" alt="cpu_usage" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/e90ee8ee-dc41-4b18-88bd-88d187889c98">

## Time VS Threads
<img width="649" alt="time_graph" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/2750c6e7-d4b4-46fb-aa28-b22a98b03109">

## Resultant Table
<img width="450" alt="res_table" src="https://github.com/RupinderRana/Multi-Threading/assets/98392235/1e39d93a-2e7f-40cb-891c-921d2be03e1e">

