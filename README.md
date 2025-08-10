
# 🔒 Deadlock Demonstration in Java

**Project:** Deadlock in Operating Systems (Java Example)  
**Author(s):** Archi Jaiswal & Team  
**Guide:** Vinam Tomar
**Institute:** SRM Institute of Science & Technology — Delhi NCR Campus

---

## 📌 Overview
Deadlock is a state in a multiprogramming environment where two or more processes are unable to proceed because each is waiting for the other to release a resource. This project demonstrates a **classic deadlock scenario** in Java using multithreading and synchronization.

---

## 🧠 What is Deadlock?
Deadlock occurs when the following **four conditions** hold simultaneously (Coffman conditions):
1. **Mutual Exclusion** — Only one process can access a resource at a time.
2. **Hold and Wait** — Processes already holding resources can request additional ones.
3. **No Preemption** — A resource can only be released voluntarily.
4. **Circular Wait** — A closed chain of processes exists, where each process holds at least one resource needed by the next process in the chain.

---

## 🛠 Tech Stack / Requirements
- Language: **Java** (JDK 8+)
- IDE: Eclipse / IntelliJ / VS Code
- No external libraries needed.

---

## 💻 How it Works
- Two threads (`Thread1` and `Thread2`) each hold a lock on one resource and try to acquire the other.
- Because of the order of lock acquisition, a circular wait occurs, causing a deadlock.

---

## 🧪 Sample Output
