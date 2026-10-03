# Lab 2: Investigating Process Lifecycles and OS Interaction

## 📌 Overview

This lab explores how C programs interact with the Linux Operating System (OS).

The practical focuses on processes, Process IDs (PID), Parent Process IDs (PPID), exit codes, standard input/output streams, process execution, and program termination.

The programs are written in C and compiled using the GCC compiler in an Ubuntu Linux environment.

---

# 📂 Project Structure

```text
Lab-3-Process-Lifecycles/
│
├── README.md
│
├── task1_alive.c
├── task2_identity.c
├── task3_exit.c
├── task4_input.c
└── task5_termination.c

## 🎯 Objectives

By completing this lab, the following concepts are demonstrated:

- Creating and executing C programs in Linux
- Compiling C programs using GCC
- Understanding long-running processes
- Monitoring active processes using `ps`
- Understanding Process ID (PID)
- Understanding Parent Process ID (PPID)
- Using `getpid()` and `getppid()`
- Using `sleep()` to control process execution
- Understanding program exit codes
- Checking exit status using `$?`
- Understanding standard input (`stdin`)
- Understanding standard output (`stdout`)
- Using conditional execution
- Understanding how a process reports success or failure to the OS

---

## 🛠️ Technologies and Tools

- **Programming Language:** C
- **Compiler:** GCC
- **Operating System:** Ubuntu Linux
- **Terminal:** Bash
- **Process Monitoring:** `ps`
- **Environment:** Docker Ubuntu container

---


