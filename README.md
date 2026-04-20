# XV-6
first time trying some os level stuff on a popular os xv-6 😅



🧠 xv6 Custom OS Experiments

This repository contains my modified version of xv6, a minimalist Unix-like operating system developed at MIT for educational purposes.
The goal of this project is to understand core OS concepts by implementing and modifying kernel features.

🚀 What is xv6?

xv6 is a simple Unix-like operating system that helps in learning:

Process management (fork, exec, wait)
Memory management (virtual memory)
File systems
System calls
Scheduling

🔧 What I’ve done in this repo
✅ Added custom system calls
✅ Explored kernel-user interaction
✅ Modified process behavior
✅ Debugged kernel-level errors
🚧 More features coming...
🛠️ Tech Stack
C (Kernel + User programs)
Assembly (low-level operations)
QEMU (emulator)
Makefile (build system)
⚙️ Setup & Run
1. Clone repo
git clone https://github.com/your-username/xv6-custom.git
cd xv6-custom
2. Install dependencies (Linux / Kali / WSL)
sudo apt update
sudo apt install build-essential qemu-system-x86
3. Run xv6
make clean
make qemu
🧪 Example Feature (Custom System Call)

Example: Added a system call to print a message from kernel space.

int sys_hello(void) {
    cprintf("Hello from kernel!\n");
    return 0;
}
📚 Learning Outcomes
Deep understanding of OS internals
Hands-on experience with kernel development
Improved debugging and low-level programming skills
🎯 Future Work
Priority-based scheduling
Memory management improvements
File system enhancements
Custom shell commands
🤝 Contributing

This is a learning project, but suggestions and improvements are welcome!

📜 License

Based on MIT xv6-public. Follow original license terms.
