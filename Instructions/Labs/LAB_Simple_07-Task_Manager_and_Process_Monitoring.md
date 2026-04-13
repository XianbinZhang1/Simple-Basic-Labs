---
lab:
  title: 'Simple Lab 07: Task Manager and Process Monitoring'
  module: Basic Computer Skills
  description: Learn to use Task Manager to monitor running programs and system performance
  duration: 12 minutes
  level: 100
  islab: true
  primarytopics:
    - Task Manager
    - Process Monitoring
    - System Performance
    - Application Management
---

# Simple Lab 07 - Task Manager and Process Monitoring

## Lab introduction

In this lab, you will learn how to use Task Manager to view running applications, monitor system performance, and manage processes. Task Manager is an essential tool for understanding what programs are running on your computer and troubleshooting performance issues.

## Estimated timing: 12 minutes

## Lab scenario

Your computer seems to be running slowly, and you want to identify which applications are consuming system resources. In this exercise, you will open Task Manager to view running processes and monitor performance metrics.

## Job skills

+ Task 1: Open Task Manager and view running applications
+ Task 2: Monitor system performance and resource usage

## Task 1: Open Task Manager and view running applications

In this task, you will open Task Manager and examine the list of running applications.

1. Open Task Manager using one of these methods:
   - **Method 1:** Right-click on the **taskbar** at the bottom and select **Task Manager**
   - **Method 2:** Press **Ctrl + Shift + Esc**
   - **Method 3:** Press **Ctrl + Alt + Delete**, then select **Task Manager**

2. The Task Manager window will open. If it shows the simplified view, click **More details** to expand it.

3. You should now see the **Processes** tab showing:
   - Application name
   - Status (Running)
   - Publisher information
   - Resource usage (CPU, Memory, Disk, Network)

4. Observe the list of running applications and processes. Some common ones include:
   - File Explorer
   - Web browsers
   - Windows system processes
   - Any applications you currently have open

5. Look for your open applications in the list (web browser, notepad, file manager, etc.).

6. Click on one of the application names to select it and observe its resource usage:
   - **CPU usage** (percentage of processor being used)
   - **Memory usage** (RAM being consumed)
   - **Disk usage** (storage read/write operations)
   - **Network usage** (internet bandwidth)

7. Sort the applications by clicking on the **Memory** column header to see which apps use the most RAM.

8. Repeat by clicking **CPU** to see which apps are consuming the most processing power.

## Task 2: Monitor system performance and resource usage

In this task, you will view overall system performance statistics.

1. Click on the **Performance** tab in Task Manager.

2. You will see four main performance graphs:
   - **CPU** - Shows processor usage over time
   - **Memory** - Shows RAM usage
   - **Disk** - Shows storage drive activity
   - **Network** - Shows internet usage

3. Observe the current percentage for each resource at the bottom right of each graph.

4. Note the **Total** and **Available** memory:
   - **Total memory:** Your computer's installed RAM
   - **Available memory:** How much RAM is free to use

5. Calculate the percentage of memory in use: (Total - Available) / Total × 100

6. Click on **CPU** to view detailed CPU information:
   - Number of cores
   - Base speed
   - Current clock speed
   - Utilization percentage

7. Return to the **Processes** tab and note which processes are consuming the most resources.

8. After completing your observation, you can close Task Manager by clicking the **X** button.

## Additional Information

**Note on terminating processes:**
- You can right-click on a process and select **End task** to close it
- Be careful when terminating system processes - only end processes you recognize
- Never terminate system critical processes like svchost.exe, System, or csrss.exe

**Performance Monitoring Tips:**
- Monitor Task Manager regularly to track system performance
- If your computer is slow, check what's using CPU and Memory
- Consider disabling unnecessary startup programs to improve performance

## Summary

In this lab, you have successfully:
- Opened Task Manager using multiple methods
- Viewed running applications and their resource usage
- Sorted processes by different resource metrics (CPU, Memory, Disk, Network)
- Accessed the Performance tab to view system-wide resource graphs
- Understood overall system performance statistics
- Learned how to identify resource-intensive applications

These Task Manager skills are essential for system troubleshooting and understanding your computer's resource allocation.
