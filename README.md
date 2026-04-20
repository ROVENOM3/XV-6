# 🧠 xv6 Custom Operating System

> ⚙️ Learning operating systems by building and modifying them from scratch.

---

## 📌 Overview

This repository contains my customized version of **xv6**, a minimalist Unix-like operating system developed at MIT.
The purpose of this project is to gain a deep understanding of **operating system concepts** through hands-on kernel development.

---

## 🚀 Key Concepts Explored

* Process Management (`fork`, `exec`, `wait`)
* Memory Management (virtual memory)
* File System operations
* System Calls (user → kernel interaction)
* CPU Scheduling

---

## 🔧 Features & Modifications

* ✅ Added custom system calls
* ✅ Explored kernel-user space interaction
* ✅ Debugged and fixed kernel-level errors
* 🚧 Ongoing experiments with scheduling and memory

---

## 🛠️ Tech Stack

* **Language:** C, Assembly
* **Tools:** QEMU (emulator), GCC, Make
* **Environment:** Linux / Kali / WSL

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ROVENOM3/XV-6.git
cd xv6-custom
```

### 2. Install dependencies

```bash
sudo apt update
sudo apt install build-essential qemu-system-x86
```

### 3. Run xv6

```bash
make clean
make qemu
```

---

## 🧪 Example: Custom System Call

```c
int sys_hello(void) {
    cprintf("Hello from kernel!\n");
    return 0;
}
```

This demonstrates how user programs interact with the kernel via system calls.

---

## 📚 Learning Outcomes

* Strong understanding of OS internals
* Practical experience with kernel programming
* Improved debugging and low-level coding skills

---

## 🎯 Future Enhancements

* Priority-based CPU scheduling
* Advanced memory management
* File system improvements
* Custom shell commands

---

## 🤝 Contributing

This is a personal learning project, but contributions and suggestions are welcome.

---

## 📜 License

Based on MIT xv6-public. Refer to original license for details.
