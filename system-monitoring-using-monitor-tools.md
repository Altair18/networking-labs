Windows System Monitoring using Performance and Resource Monitor tools

This project showcases my use of Windows built-in monitor tools to analyze system behavior under simulated load. This is part of my learning and demonstration for system and network monitoring in real-world environments.

Tools Used:
1: Performance Monitor: Used to track CPU ulitization over time and provides a clear visual of system response to workloads.
2: Resource Monitor: Used to monitor varies components such as CPU, Disk, Network and Memory usage in real-time.

What I Did:
Used Resource Monitor to inspect which processes were using the most resources (CPU, Memory, etc)
Captured system behaviour on my system of using it for 2 minutes to track changes over time
Simulated increased workloads by launching multiple browser tabs and background applications

What I Saw
After opening multiple browser tabs and increasing the number of applications in used, I observed a significant spike in CPU usage with microsoft edge being the main contributer to this
Memory usage remained low, indicating that the system wasn't under memory pressure.

<img width="1372" height="780" alt="performance-monitor" src="https://github.com/user-attachments/assets/fa34e158-70d8-47f2-9eac-72c8ba1d6e90" />
<img width="1465" height="777" alt="resource-monitor" src="https://github.com/user-attachments/assets/1338fbe6-6943-4249-a58f-9f9adc0dd458" />


Why
Monitoring tools like these are essential for:
Diagnosing system or network bottlenecks.
Used for troubleshooting
Ensure healthy performance across system
