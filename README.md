
# **System Management Tools**

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

### **Example Outputs**
- **Option 1:** Lists all processes in the following format:  
  ```
  USER       PID  %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
  root      1234   0.0  0.1  123456 2345 ?        S    10:00   0:01 /usr/bin/some_process
  ```
- **Option 2:** Prompts for a PID and confirms the process termination.
- **Option 3:** Prompts for a username and shows their processes.
- **Option 4:** Displays the top 5 CPU/memory-consuming processes.
- **Option 5:** Logs process statuses to `process_logs.txt` every minute.

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

### **Example Outputs**
- **Option 1:** Displays current CPU usage:
  ```
  CPU Usage: 12.5%
  ```
- **Option 2:** Tracks CPU usage over time and logs:
  ```
  [10:00 AM] CPU Usage: 12.5%
  [10:01 AM] CPU Usage: 14.8%
  ```
- **Option 3:** Prompts for a PID and CPUs to set affinity.
- **Option 4:** Alerts:  
  ```
  Warning: CPU Usage exceeded 90%!
  ```

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

### **Example Outputs**
- **Option 1:** Displays memory usage:
  ```
  Total: 8192MB | Used: 5120MB | Free: 3072MB
  ```
- **Option 2:** Lists processes consuming over a threshold:
  ```
  PID    USER   %MEM   COMMAND
  1234   root   20.0   /usr/bin/java
  ```
- **Option 3:** Clears cache:
  ```
  Cache and buffers cleared successfully.
  ```
- **Option 4:** Alerts for low memory:
  ```
  Warning: Available memory below 100MB!
  ```

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

### **Example Outputs**
- **Option 1:** Shows disk usage:
  ```
  Filesystem      Size  Used Avail Use% Mounted on
  /dev/sda1        50G   30G   20G  60% /
  ```
- **Option 2:** Lists largest files:
  ```
  1. /home/user/file1.log (1.2GB)
  2. /var/log/syslog (800MB)
  ```
- **Option 3:** Displays modified files in 24 hours:
  ```
  /home/user/document.txt (Modified: 10:00 AM)
  ```
- **Option 4:** Removes large temporary files in `/tmp`.

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

### **Example Outputs**
- **Option 1:** Displays active interfaces:
  ```
  eth0: 192.168.1.2 (UP)
  wlan0: 10.0.0.1 (UP)
  ```
- **Option 2:** Shows bandwidth usage:
  ```
  Interface: eth0 | Download: 1.2MB/s | Upload: 300KB/s
  ```
- **Option 3:** Alerts:
  ```
  Alert: Connection detected from 192.168.1.10!
  ```
- **Option 4:** Logs traffic:
  ```
  [10:00 AM] eth0: 1.2MB/s Down | 300KB/s Up
  ```

---

## **License**
Released under the MIT License.

