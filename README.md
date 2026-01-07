# 🧠 Synth OS: Memory & Scheduling Simulator 🚀

Welcome to **Synth OS**, a gamified educational platform designed to help students visualize and master Operating Systems concepts! This project was built to simplify the complexities of **Best-Fit Memory Allocation** and **Priority Scheduling** through an interactive, synth-wave-inspired interface.

🔗 **Live Demo:** [synth-os-code.lovable.app](https://synth-os-code.lovable.app/memory-allocation)

---

## 🌟 Features

* **🎮 Gamified Learning:** Interactive UI to simulate complex OS algorithms without the dry textbook feel.
* **💾 Best-Fit Allocation:** Visualize how the OS scans memory blocks to find the smallest hole that is "just right" for a process, minimizing wasted space.
* **⏳ Priority Scheduling:** Watch processes get queued and executed based on assigned priority levels with real-time Gantt-style updates.
* **⚡ Modern Stack:** Built with a focus on performance and a responsive layout that works across devices.

---

## 🛠️ Tech Stack

* **Frontend:** React + Vite
* **Styling:** Tailwind CSS + Shadcn UI
* **Icons:** Lucide React
* **Language:** TypeScript
* **Platform:** Generated & Hosted via [Lovable](https://lovable.dev)

---

## 🚀 Getting Started

To run this project locally, follow these steps:

### 📋 Prerequisites

Ensure you have the following installed:
* **Node.js** (v18.0 or higher)
* **npm** or **bun**

### 🔧 Installation & Build

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/synth-os.git](https://github.com/YOUR_USERNAME/synth-os.git)
    cd synth-os
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```
    The application will be available at `http://localhost:8080`.

4.  **Build for production:**
    ```bash
    npm run build
    ```
    The production-ready files will be located in the `dist/` directory.

---

## 📖 How It Works

### Best-Fit Memory Allocation
The algorithm searches the entire list of free memory blocks and allocates the process to the smallest block that is large enough. This helps in keeping the leftover free blocks as small as possible, though it requires a full search of memory.

### Priority Scheduling
Each process is assigned a priority (usually a numerical value). The CPU is allocated to the process with the highest priority. Our simulator handles both the visualization of the queue and the execution order.

---

## 📂 Project Structure

```text
├── src/
│   ├── components/  # UI components (Memory blocks, Process cards)
│   ├── hooks/       # Logic for allocation and scheduling algorithms
│   ├── lib/         # Utility functions and constants
│   └── pages/       # Main views (MemoryAllocation.tsx, Scheduling.tsx)
├── public/          # Assets and static files
└── vite.config.ts   # Build configuration

## 📸 Screenshots
<img width="1909" height="1079" alt="image" src="https://github.com/user-attachments/assets/80843871-4071-4cb2-8695-d71901becec6" />
<img width="1905" height="1017" alt="image" src="https://github.com/user-attachments/assets/24fe708d-9be4-4e51-a8d4-5241b6ed7996" />
<img width="1898" height="1079" alt="image" src="https://github.com/user-attachments/assets/bed4e7d3-9869-4e87-b4e4-339cc954c22f" />
<img width="1909" height="656" alt="image" src="https://github.com/user-attachments/assets/50563d8c-551a-4d82-bd87-ff52c4c5215a" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c30b0180-231a-4091-95dc-5344fcd3aa6d" />
