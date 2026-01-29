DCIT 301 – Process Scheduler System

📌 Project Overview

The Process Scheduler System is a CPU scheduling simulation developed as part of DCIT 301 (Operating Systems). The project implements and evaluates traditional CPU scheduling algorithms and introduces an intelligent scheduling approach aimed at improving performance in dynamic workloads.

The system allows users to simulate process execution, observe scheduling behavior, and analyze performance metrics such as waiting time, turnaround time, and CPU utilization.


---

🎯 Objectives

Implement and analyze traditional CPU scheduling algorithms

Demonstrate the limitations of static scheduling techniques

Introduce a predictive/intelligent scheduling approach

Compare performance using standard evaluation metrics



---

⚙️ Features

Simulation of multiple CPU scheduling algorithms

Modular and extensible system design

Performance evaluation and comparison

Optional graphical interface (Tkinter)

Clear separation of scheduling logic and data handling



---

🧠 Scheduling Algorithms Implemented

First Come First Serve (FCFS)

Shortest Job First (SJF)

Round Robin (RR)

Intelligent / Predictive Scheduler (Proposed)



---

🏗️ System Architecture

The system follows a modular architecture consisting of:

User Interface (CLI / GUI)

Scheduler Core

Process Data Manager

Prediction Module

Evaluation & Metrics Module


This design ensures scalability, maintainability, and ease of testing.


---

🛠️ Technologies Used

Programming Language: Python

GUI Library: Tkinter 

Visualization: Matplotlib

Version Control: Git & GitHub



---

📂 Project Structure

DCIT-301-PROCESS-SCHEDULER-SYSTEM/
│── main.py
│── scheduler.py
│── task_manager.py
│── requirements.txt
│── README.md


---

▶️ How to Run the Project

1. Clone or download the repository



git clone https://github.com/Cedric-Raichand/DCIT-301-PROCESS-SCHEDULER-SYSTEM.git

2. Navigate to the project directory



cd DCIT-301-PROCESS-SCHEDULER-SYSTEM

3. Install required dependencies



pip install -r requirements.txt

4. Run the application



python main.py



📊 Performance Metrics Evaluated

1. Average Waiting Time

2. Average Turnaround Time

3. CPU Utilization

4. Throughput


These metrics are used to compare the effectiveness of each scheduling algorithm.



🧪 Testing Methodology

The system was tested using simulated workloads with varying arrival times and burst durations. Each scheduling algorithm was evaluated using identical inputs to ensure fair comparison.



🚧 Limitations

Assumes CPU-bound processes only

Limited machine learning complexity

Does not fully simulate I/O blocking or multi-core environments




🔮 Future Enhancements

Integration of advanced machine learning models

Support for real-time and priority-based scheduling

Web-based visualization dashboard

Multi-core CPU scheduling simulation





👨‍💻 Contributors

CEDRIC 22046156
OWUSU SARFO 22078485
DESMOND SEDEM 22101911
LAMBERT KLENAM 22165472
TETTEH JOEL 22182128
TIMOTHY EZEKIEL 22044041
STEPHANIE OSANI 22044374
TETTEH BELINDA 22241719

DCIT 301 – Operating Systems



📜 License

This project is for academic purposes only.
