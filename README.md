      /\/\   ___  _ __ (_) |_ ___  _ _\ \/ /
     /    \ / _ \| '_ \| | __/ _ \| '__\  /
    / /\/\ \ (_) | | | | | || (_) | |  /  \
    \/    \/\___/|_| |_|_|\__\___/|_| /_/\_\

# MonitorX
A lightweight and user-friendly tools for monitoring system resources with customizable thresholds and reporting options.

## Overview
MonitorX is a comprehensive tool that provides real-time monitoring of CPU, memory, and disk usage. It features customizable alert thresholds, colorized output for better visibility, and flexible reporting options including both command-line display and file output capabilities.

## Prerequisites
The script requires the following utilities to be installed on your system:

top - for CPU monitoring

free - for memory analysis

df - for disk space monitoring

bc - for floating-point calculations

## Installation
Clone the repository or download the script:
```git clone https://github.com/Qilzxz/MonitorX.git```
Make the script executable
```chmod +x Monitorx.sh```

## Usage
The script can be run in two modes:
1. Display results in terminal
```./Monitorx.sh -nf```
2. Display results to a file
```./Monitorx.sh -f output.txt```

## Output Example
When running with the -nf option, you'll see output similar to this:

![Screenshot 2025-02-14 005455](https://github.com/user-attachments/assets/c0e39847-09bb-4b07-a9e6-b93d67ca69f9)
