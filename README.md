# 🖥️ OS Scheduler Visualizer

This project is a simple **Operating System CPU Scheduling Simulator** written in **C/C++**.  
It helps visualize how different CPU scheduling algorithms work such as:

- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- Round Robin (RR)
- Priority Scheduling

---

## 🚀 Features
- Takes input for process IDs, burst time, arrival time, and priority.
- Simulates CPU scheduling algorithms step by step.
- Displays average **waiting time** and **turnaround time**.
- Visualizes **Gantt Chart** for better understanding.
- Simple, fast, and easy to modify for learning OS concepts.

---

## 🧠 Algorithms Implemented
| Algorithm | Description |
|------------|--------------|
| FCFS | Executes processes in the order they arrive. |
| SJF | Selects the process with the smallest burst time next. |
| Priority | Executes processes based on their priority number. |
| Round Robin | Each process gets an equal share of CPU in time slices. |

---

## 🛠️ Compilation and Execution
### Using GCC:
```bash
gcc os_scheduler_visualizer.c -o scheduler
./scheduler

Using G++ (for C++ version):
g++ os_scheduler_visualizer.cpp -o scheduler
./scheduler

📚 Concepts Used

Process Scheduling

Queues

CPU Burst & Arrival Times

Gantt Chart Representation

Average Waiting & Turnaround Times

🧑‍💻 Author

Manmeet Kaur
📘 BCA Graduate | 💻 Aspiring Software Developer
🌐 LinkedIn Profile : https://www.linkedin.com/in/manmeet-kaur-245a372ba/
⭐ If you like this project, give it a star on GitHub!
