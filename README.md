# 🐍 Snake Game in x86 Assembly Language

A classic **Snake Game** implemented entirely in **x86 Assembly Language** using BIOS and DOS interrupts.  
This project was developed as a **pair project during my 4th semester** to strengthen low-level programming concepts and understanding of hardware-level operations.

---

## 📌 Project Type
**Academic Pair Project**

Developed collaboratively with a teammate as part of university coursework.

---

## 👥 Team Members
- **Muhammad Ali**
- **Areeba Noor**

---

## ✨ Features
- Fully functional Snake gameplay in text mode  
- Queue-based implementation of snake body (without high-level libraries)  
- Real-time keyboard input using BIOS interrupts  
- Direct manipulation of video memory (`0xB800`)  
- Score and lives tracking system  
- Wall and self-collision detection  
- Pseudo-random food generation  
- Game restart and exit functionality  

---

## 🛠️ Technologies & Concepts Used
- x86 Assembly Language  
- BIOS Interrupts (`INT 10h`, `INT 16h`)  
- DOS Interrupts (`INT 21h`)  
- Text-mode video memory (80×25)  
- Low-level memory addressing  
- Queue data structure implementation  

---

## ▶️ How to Run the Game
1. Use an emulator such as **DOSBox**
2. Assemble and run the program using an assembler like **NASM*
