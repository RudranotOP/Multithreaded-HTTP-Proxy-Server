# 🌐 Multithreaded HTTP Proxy Server

<div align="center">

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa3A2cW9zZTB0NXA4N2JrNnBwaWRzcm5nZm9uZW9lN2Nmc2ZsZTZ0eiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/l0HlQXkh1wx1RjtUA/giphy.gif" width="260" />

# 🌐 Multithreaded HTTP Proxy Server

### ⚡ High-Performance Concurrent Networking System

> A systems-level HTTP proxy server built using low-level networking, multithreading, synchronization primitives, and caching mechanisms.

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/POSIX_Sockets-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pthreads-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mutexes_&_Semaphores-blue?style=for-the-badge" />
</p>

</div>

---

## 🎥 Demo Preview

<p align="center">
  <img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="700" />
</p>

---

## 🚀 Overview

This project implements a **custom multithreaded HTTP proxy server** capable of handling multiple client requests concurrently while ensuring thread safety and optimized performance.

The server also integrates an **LRU (Least Recently Used) cache mechanism** to reduce redundant requests and improve response speed.

Built entirely in **C++ using low-level OS and networking concepts**, this project demonstrates deep understanding of:

* operating systems,
* concurrency,
* memory synchronization,
* and socket programming.

---

## 🧠 Core Problem Solved

### Modern web systems face:

* Race conditions in concurrent environments ❌
* Unsafe shared memory access ❌
* High latency from repeated requests ❌
* Thread synchronization issues ❌

### This project solves them through:

* Concurrent multithreaded request handling
* Mutex & semaphore-based synchronization
* Efficient LRU caching strategy
* Safe shared resource management

---

## ⚙️ Tech Stack

| Category        | Technologies        |
| --------------- | ------------------- |
| Language        | C++                 |
| Networking      | POSIX Sockets       |
| Concurrency     | Pthreads            |
| Synchronization | Mutexes, Semaphores |
| Optimization    | LRU Cache           |

---

## 🔥 Key Features

### ⚡ Concurrent Request Handling

Handles multiple client requests simultaneously using multithreading.

### 🧠 Thread-Safe Memory Management

Uses synchronization primitives to prevent race conditions.

### 📦 LRU Cache System

Optimizes repeated requests and minimizes latency.

### 🌐 HTTP Request Forwarding

Acts as an intermediary between clients and web servers.

### 🔒 OS-Level Synchronization

Implements mutex locks and semaphores for safe concurrency.

---

## 🧩 System Design Highlights

```txt
Client Requests
      ↓
Proxy Server Listener
      ↓
Thread Pool / Worker Threads
      ↓
Mutex-Synchronized Shared Resources
      ↓
LRU Cache Lookup
      ↓
Remote HTTP Server
      ↓
Response Returned To Client
```

---

## 🖼 Architecture Visualization

<p align="center">
  <img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" width="700" />
</p>

---

## 📌 Engineering Highlights

* Producer-consumer thread model
* Kernel-level socket management
* Shared memory synchronization
* Efficient cache eviction algorithm
* Low-level networking architecture
* High-concurrency system handling

---

## 📌 Impact

✅ Demonstrates strong OS + networking fundamentals
✅ Simulates real-world proxy server architecture
✅ Proves concurrency & synchronization understanding
✅ Highlights low-level systems engineering skills
✅ Shows production-style performance optimization thinking

---

## 📷 Future Improvements

* 🔐 HTTPS support (SSL tunneling)
* ⚖️ Load balancing layer
* 🛡 Request filtering/firewall module
* 📊 Performance benchmarking dashboard
* 🌍 Distributed proxy architecture

---

## 🛠 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/http-proxy-server.git

# Navigate into project
cd http-proxy-server

# Compile source code
g++ proxy.cpp -lpthread -o proxy

# Run proxy server
./proxy
```

---

## 👨‍💻 Author

### Rudra Prasad Lugun

> Systems Programming • Networking • Concurrent Systems

---

<div align="center">

### ⭐ If you like this project, consider starring the repository!

<img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="120" />

</div>
