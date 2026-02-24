# 🖥️ Smart CPU Scheduling Simulator

A Python-based simulator that demonstrates core CPU scheduling algorithms used in Operating Systems, built with Object-Oriented Programming principles.

---

## 📌 Overview

This project simulates three fundamental CPU scheduling algorithms:

- **FCFS** – First Come First Serve
- **SJF** – Shortest Job First (Non-Preemptive)
- **Priority Scheduling**

For each algorithm, the simulator calculates and displays:

- Waiting Time per process
- Turnaround Time per process
- Average Waiting Time
- Average Turnaround Time

---

## 🎯 Objective

To demonstrate a practical implementation of OS scheduling concepts through clean, object-oriented Python code — making it useful for learning, experimentation, and academic reference.

---

## 🛠️ Tech Stack

| Technology | Details |
|---|---|
| Language | Python 3 |
| Paradigm | Object-Oriented Programming (OOP) |
| Dependencies | None (standard library only) |

---

## 📁 Project Structure

```
cpu-scheduler/
│
├── cpu_scheduler.py      # Main simulator file
└── README.md             # Project documentation
```

---

## ▶️ How to Run

**Prerequisites:** Python 3.x installed on your system.

**Clone the repository:**
```bash
git clone https://github.com/your-username/cpu-scheduler.git
cd cpu-scheduler
```

**Run the simulator:**
```bash
python cpu_scheduler.py
```

---

## 🔍 Algorithms Explained

### 1. FCFS – First Come First Serve
Processes are executed in the order they arrive. Simple but can lead to the **convoy effect**, where short processes wait behind long ones.

### 2. SJF – Shortest Job First (Non-Preemptive)
The process with the shortest burst time is selected next. Minimizes average waiting time but may cause **starvation** of longer processes.

### 3. Priority Scheduling
Each process is assigned a priority. The CPU is allocated to the highest-priority process first. Ties can be broken using FCFS order.

---

## 📊 Sample Output

```
===== FCFS Scheduling =====
Process  Burst Time  Waiting Time  Turnaround Time
P1       6           0             6
P2       4           6             10
P3       8           10            18

Average Waiting Time    : 5.33
Average Turnaround Time : 11.33
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to add new algorithms (e.g., Round Robin, SRTF) or improve existing ones.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/round-robin`)
3. Commit your changes (`git commit -m 'Add Round Robin scheduling'`)
4. Push to the branch (`git push origin feature/round-robin`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author

Made with ❤️ for OS enthusiasts and students exploring scheduling algorithms.
