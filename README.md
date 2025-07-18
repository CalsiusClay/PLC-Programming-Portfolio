# 🧠 PLC Programming Portfolio – Nathanael K. Binu (@kermitsmittle)

Welcome to my PLC Programming Portfolio! This repo documents my journey into the world of industrial automation and control systems, with a laser focus on **Structured Text (ST)** and the **CODESYS V3** platform.

From humble timer projects to a full-scale HVAC simulation—and a bunch of Reddit rabbit-hole problems in between—this portfolio shows what I’ve built, broken, debugged, and improved.

---

## ⚙️ Tools & Environment

- 🧠 **IDE**: CODESYS Development System V3  
- 💻 **Runtime**: CODESYS Control Win  
- 🔄 **Comms**: CODESYS Gateway  
- 🎮 **Testing**: Simulation Mode  
- 🧾 **Language**: Structured Text (IEC 61131-3)

---

## 📚 Project Categories

### 🔹 Timers & Basics
Fundamental control logic examples using:
- `TON` – On-Delay Timer
- `TOF` – Off-Delay Timer
- `TP` – Pulse Timer
- `CTU` / `CTD` – Counters
- Bit logic and relay simulations

### 🔹 Reddit Practice Problems
Real-world logic puzzles & “what-would-you-do” scenarios from Reddit’s automation community:
- All problems documented
- Solutions explained with comments
- Simulated if possible

### 🔹 Mini Applications
Bite-sized demos showcasing:
- Arithmetic & comparison logic
- Rising/falling edge detection
- Flip-flop implementations
- PID controller mockups

### 🔹 HVAC Project (Main Demo)
Simulation of a hospital HVAC system that handles 16–20 surgeries per day:
- Modular Function Blocks for AHUs, chillers, sensors
- Mode control: Manual/Auto
- Fault detection & alarms
- Designed for scalability and reuse

---

## 🔥 Why This Exists

I built this repo to:
- Track my **learning** with real, working code
- Reinforce **industry-ready practices** (naming, comments, structure)
- Solve **community problems** with transparency
- Grow as a future **Controls Integrator** through real feedback

Also, because solving Reddit problems is like playing Sudoku… if Sudoku could electrocute you.

---

## 🚀 Getting Started

1. Install [CODESYS V3](https://www.codesys.com/download.html)
2. Clone this repo
3. Open the desired project folder in CODESYS
4. Set device to "CODESYS Control Win (V3)"
5. Hit **Login**, **Download**, and run the simulation

Test tags and logic are commented in each program for easy understanding.

---

## 📈 Roadmap

- ✅ Build TON/TOF examples  
- ⏳ Add Reddit solutions with Markdown explanations  
- 🔁 Add sequence logic and counter libraries  
- 🏥 Create reusable Function Blocks for HVAC logic  
- 📦 Publish custom libraries for timers/PIDs  
- 🔐 Explore Modbus TCP & Ethernet protocols  
- 🖥️ Simulate with basic HMI elements (optional stretch goal)

---

## 👨‍💻 About the Author

Hey there! I’m **Nathanael K. Binu**, a PLC programming enthusiast, structured-text maximalist, and future Controls Engineer.  
On Reddit, I go by **@kermitsmittle**—where I test my skills by helping others (and stealing their bugs to learn from).

This repo is my personal lab, sandbox, and logbook—documenting how I go from blinking a virtual light… to controlling a surgical-grade HVAC system.

> “Code like your panel depends on it.” – Me, halfway into a debugging spiral

---

## 🙌 Got Feedback?

If you found a bug, want to suggest a better way to handle timers, or just have a cool Reddit problem to tackle—open an issue or drop it on [r/PLC](https://www.reddit.com/r/PLC/). I'm always down to learn more or break things together.

---

### 🌟 Star this repo if:
- You're learning CODESYS or ST  
- You like nerdy portfolios  
- You believe timers deserve more respect