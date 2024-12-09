
# **Linux OS Management Script Suite**
**Name(s):** Sher, Hanna, and Yahya  
**Student Number(s):** 991490409, 991622474

This repository contains five tools to monitor and manage system processes, CPU usage, memory usage, file systems, and network activity. Each script provides a menu-driven interface for easy interaction.

---

## **1. process_manager_tool.sh**

### **Description**
The `process_manager_tool.sh` script allows you to manage and monitor system processes.

### **Usage**
```bash
bash process_manager_tool.sh
```

### **Options**
| Option | Description                                       |
|--------|---------------------------------------------------|
| `1`    | List all running processes (PID, user, CPU, memory). |
| `2`    | Kill a process by its PID.                       |
| `3`    | Display processes running by a specific user.    |
| `4`    | Show the top 5 processes consuming the most CPU and memory. |
| `5`    | Schedule process status checks every minute and save to `process_logs.txt`. |
| `6`    | Exit the tool.                                   |

---

## **2. cpu_manager_tool.sh**

### **Description**
The `cpu_manager_tool.sh` script monitors and analyzes CPU usage.

### **Usage**
```bash
bash cpu_manager_tool.sh
```

### **Options**
| Option | Description                                          |
|--------|------------------------------------------------------|
| `1`    | Display current CPU usage percentage.               |
| `2`    | Track CPU usage over time and save to `cpu_usage_logs.txt`. |
| `3`    | Set CPU affinity for a process (assign it to specific CPUs). |
| `4`    | Monitor CPU usage and alert if it exceeds 90%.      |
| `5`    | Exit the tool.                                      |

---

## **3. memory_manager_tool.sh**

### **Description**
The `memory_manager_tool.sh` script monitors and manages system memory.

### **Usage**
```bash
bash memory_manager_tool.sh
```

### **Options**
| Option | Description                                          |
|--------|------------------------------------------------------|
| `1`    | Display current memory usage (total, used, free).    |
| `2`    | List processes consuming high memory.               |
| `3`    | Clear cache and buffers to free up memory.          |
| `4`    | Check for low memory alerts (threshold: 100MB).     |
| `5`    | Exit the tool.                                      |

---

## **4. file_system_monitor_tool.sh**

### **Description**
The `file_system_monitor_tool.sh` script monitors disk usage and file changes.

### **Usage**
```bash
bash file_system_monitor_tool.sh
```

### **Options**
| Option | Description                                          |
|--------|------------------------------------------------------|
| `1`    | Display disk usage for each mounted filesystem.      |
| `2`    | List the top 15 largest files in a directory.        |
| `3`    | Show files modified in the last 24 hours.           |
| `4`    | Remove temporary files exceeding a specified size.   |
| `5`    | Exit the tool.                                      |

---

## **5. network_monitor_tool.sh**

### **Description**
The `network_monitor_tool.sh` script manages and monitors network activity.

### **Usage**
```bash
bash network_monitor_tool.sh
```

### **Options**
| Option | Description                                          |
|--------|------------------------------------------------------|
| `1`    | Display IP addresses and statuses of active interfaces. |
| `2`    | Show bandwidth usage for each interface.            |
| `3`    | Monitor network connections and alert for specific IPs. |
| `4`    | Track network traffic over time and save to logs.    |
| `5`    | Exit the tool.                                      |

---

## **License**
Released under the MIT License.
