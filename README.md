
# System Management Tools

This repository contains five tools to monitor and manage system processes, CPU usage, memory usage, file systems, and network activity. Each script provides a menu-driven interface for easy interaction.

---

## 1. **process_manager_tool.sh**

### **Description**
The `process_manager_tool.sh` script provides a menu-driven tool to monitor and manage processes on a Linux system.

### **Usage**
To run the script, execute:
```bash
bash process_manager_tool.sh
```

### **Options**
When prompted, choose an option by entering the corresponding number:

| Option | Description                          |
|--------|--------------------------------------|
| `1`    | List all running processes.          |
| `2`    | Kill a process (enter its PID).      |
| `3`    | Display resource usage per process.  |
| `4`    | Search for a process by name.        |
| `5`    | Exit the tool.                       |

### **Example Run**
```bash
bash process_manager_tool.sh
```
**Output:**
```
Choose an option:
1. List all processes
2. Kill a process
3. Show resource usage
4. Search for a process
5. Exit
Enter your choice: 1
```

---

## 2. **cpu_manager_tool.sh**

### **Description**
The `cpu_manager_tool.sh` script provides a simple menu to monitor CPU usage and performance metrics.

### **Usage**
To run the script, execute:
```bash
bash cpu_manager_tool.sh
```

### **Options**
Choose an option when prompted:

| Option | Description                        |
|--------|------------------------------------|
| `1`    | Display current CPU usage.         |
| `2`    | Show CPU load averages.            |
| `3`    | Display CPU core information.      |
| `4`    | View processes by CPU usage.       |
| `5`    | Exit the tool.                     |

### **Example Run**
```bash
bash cpu_manager_tool.sh
```
**Output:**
```
Choose an option:
1. Display CPU usage
2. Show CPU load averages
3. Display CPU core details
4. View processes sorted by CPU usage
5. Exit
Enter your choice: 2
```

---

## 3. **memory_manager_tool.sh**

### **Description**
The `memory_manager_tool.sh` script is a menu-based utility for monitoring and managing system memory usage.

### **Usage**
To run the script, execute:
```bash
bash memory_manager_tool.sh
```

### **Options**
Select an option from the menu:

| Option | Description                       |
|--------|-----------------------------------|
| `1`    | Display total memory usage.       |
| `2`    | Show free and used memory stats.  |
| `3`    | Display swap memory usage.        |
| `4`    | List processes by memory usage.   |
| `5`    | Exit the tool.                    |

### **Example Run**
```bash
bash memory_manager_tool.sh
```
**Output:**
```
Choose an option:
1. Display memory usage summary
2. Show free and used memory
3. Display swap memory usage
4. List processes sorted by memory usage
5. Exit
Enter your choice: 1
```

---

## 4. **file_system_monitor_tool.sh**

### **Description**
The `file_system_monitor_tool.sh` script provides options to monitor and manage file system usage and disk space.

### **Usage**
To run the script, execute:
```bash
bash file_system_monitor_tool.sh
```

### **Options**
Choose an option when prompted:

| Option | Description                        |
|--------|------------------------------------|
| `1`    | Display disk usage summary.        |
| `2`    | Show free and used space by mount. |
| `3`    | Monitor file changes in real-time. |
| `4`    | List largest files/directories.    |
| `5`    | Exit the tool.                     |

### **Example Run**
```bash
bash file_system_monitor_tool.sh
```
**Output:**
```
Choose an option:
1. Display disk usage summary
2. Show free and used space
3. Monitor file changes
4. List largest files
5. Exit
Enter your choice: 1
```

---

## 5. **network_monitor_tool.sh**

### **Description**
The `network_monitor_tool.sh` script allows users to monitor network activity, connections, and bandwidth usage.

### **Usage**
To run the script, execute:
```bash
bash network_monitor_tool.sh
```

### **Options**
Select an option from the menu:

| Option | Description                       |
|--------|-----------------------------------|
| `1`    | Display active network connections. |
| `2`    | Monitor network bandwidth usage.   |
| `3`    | List listening ports and services. |
| `4`    | Test network latency (ping test).  |
| `5`    | Exit the tool.                    |

### **Example Run**
```bash
bash network_monitor_tool.sh
```
**Output:**
```
Choose an option:
1. Display active network connections
2. Monitor network bandwidth
3. List listening ports
4. Test network latency
5. Exit
Enter your choice: 2
```

---

## License
Released under the MIT License.
