# 42 Common Core 🚀

Welcome to my central hub for the 42 Curriculum! This repository tracks my progress, projects, and low-level engineering skills acquired throughout the Common Core program at **42 Lausanne**. 

---

## 🗺️ Project Roadmap

| Circle | Project | Focus | Tech Stack | Status |
| :---: | :--- | :--- | :---: | :---: |
| **0** | [libft](https://github.com/b-massot/0-libft) | Re-coding standard C library functions & basic data structures | `C` | ✅ Completed |
| **1** | [get_next_line](https://github.com/b-massot/1-get_next_line) | Dynamic I/O buffering and static variable state persistence | `C` | ✅ Completed |
| **1** | [ft_printf](https://github.com/b-massot/1-ft_printf) | Re-engineering formatted outputs using variadic arguments | `C` | ✅ Completed |
| **1** | [born2beroot](https://github.com/b-massot/1-born2beroot) | System administration, encrypted LVM storage, and automation | `Debian` `Bash` | ⏳ In Progress |
| **2** | [push_swap](https://github.com/b-massot/2-push_swap) | Algorithmic optimization and constrained stack sorting | `C` | ✅ Completed |
| **2** | [minitalk](https://github.com/b-massot/2-minitalk) | Inter-process communication using raw Unix software signals | `C` | ✅ Completed |
| **2** | [so_long](https://github.com/b-massot/2-so_long) | 2D top-down game engine using pixel buffers and matrix parsing | `C` `MiniLibX` | ✅ Completed |
| **3** | [minishell](https://github.com/b-massot/3-minishell) | Designing a functional CLI command interpreter (Bash clone) | `C` | ✅ Completed |
| **3** | [philosophers](https://github.com/b-massot/3-philosophers) | Concurrency, multi-threading management, and mutex safety | `C` | ✅ Completed |
| **4** | [cub3d](https://github.com/b-massot/4-cub3d) | 3D raycasting graphical engine utilizing linear algebra | `C` `MiniLibX` | ✅ Completed |
| **4** | [netpractice](https://github.com/b-massot/4-NetPractice) | Structural network addressing, CIDR subnets, and routing logic | `Network` | ✅ Completed |
| **5** | `webserv` | HTTP/1.1 server building from scratch with non-blocking I/O | `C++98` | 🚀 Current Focus |

---

## 🧠 Core Focus & Technical Highlights

### 🔧 System & Architecture
* **Webserv:** Building an HTTP/1.1 compliant server from scratch using C++98, handling non-blocking network I/O multiplexing (`select`/`poll`/`epoll`).
* **Minishell:** Engineered a complete command-line interface managing process lifecycles (`fork`, `execve`), input pipelines (`pipe`), and signal disruptions.
* **Born2beroot:** Deploying a secure headless Debian installation enforcing strict password policies via `libpam-pwquality` and shell automation scripts (`monitoring.sh`).

### 🔢 Algorithms & Resource Management
* **Philosophers:** Solved the classic Dining Philosophers concurrency problem using POSIX threads (`pthread`) and data race shielding (`pthread_mutex`).
* **Push_swap:** Implemented highly optimized mechanical/radix sorting mechanics reducing operation complexity from $O(n^2)$ down to $O(n \log n)$.
* **get_next_line:** Created a reliable runtime reader optimizing dynamic memory allocations and tracking streams natively via File Descriptors (FD).

### 🎮 Graphics & Mathematics
* **Cub3D:** Authored a first-person perspective 3D canvas utilizing vector calculations to handle wall distance projections and custom texture mapping.
* **So_long:** Built an event-driven 2D gameplay architecture executing window event hooks, sprite rendering, and valid structural map validations.

---

## 🛠️ Developed Engineering Skills

* **Defensive Programming:** Writing strict, defensive imperative code compliant with the 42 Norminette standard.
* **Memory Architecture:** Strict tracking of execution allocations, wiping memory leaks, and eliminating dangling pointers via memory sanitizers.
* **Network Infrastructure:** Designing routing paths, debugging OSI model layers, and dealing with native socket programming.
<!--
## 🛠️ Skills Developed
* **Imperative Programming**: Writing clean, defensive code in C following strict Norminette rules.
* **Memory Management**: Identifying and patching memory leaks using Valgrind or Leaks.
* **Data Structures**: Implementing dynamic arrays, linked lists, and basic algorithmic sorting optimizations.
-->


