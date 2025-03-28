# G-Yantra Project: 8051 Game Boy Replica

## 📌 Project Overview
The **G-Yantra Project** is an innovative attempt to replicate the retro gaming experience of Nintendo's Gameboy using an **8051 microcontroller**. Developed as part of Academic Pursuits of Understanding Embedded Systems, this project focuses on hardware interfacing, game development, and delivering smooth gameplay on an 8-bit system.

## 🛠 Key Features
- **128x64 GLCD Display:** Provides the graphical interface for gameplay.
- **Two Classic Games:**
  - **Snake Game:** Navigate a growing snake to collect food while avoiding collisions.
  - **4-in-a-Row Game:** A strategic game where players aim to connect four pieces in a row.
- **Button-Based Controls:** Utilizes a custom-built 8×1 keypad for responsive user inputs.
- **Assembly Language Implementation:** Offers direct hardware control and an in-depth look at embedded system design.

## 🎯 Objectives
- Develop a **fully functional Gameboy-like system** using an 8051 microcontroller.
- Interface a **128x64 GLCD** for real-time graphics rendering.
- Implement engaging gameplay mechanics for both the **Snake Game** and **4-in-a-Row Game**.
- Efficiently manage limited memory and processing power without making performance tweaks the sole highlight.

## 🔧 Implementation Details
### Hardware Components:
- **8051 Microcontroller (AT89S52)**
- **128x64 Graphical LCD (GLCD)**
- **Custom 8×1 Keypad** for game controls
- **Power Supply Unit** and supporting circuitry
- **Programming Interface (8051 Burner)**

### Software Tools:
- **Keil µVision** for assembly language development (2k Size Limitation on Free Version).
- **MCU 8051 IDE** for assembly language development (No Size Limitation Issue).
- **Proteus** for circuit simulation and testing.
- **Prog ISP** for programming the microcontroller.

## 🚀 Game Mechanics
### Snake Game
- **Control:** The snake’s direction is managed via button inputs.
- **Gameplay:** The snake grows as it consumes food pellets. The game ends if the snake collides with itself or the screen boundaries.
- **Graphics:** Smooth, real-time updates on the GLCD maintain engaging action.

### 4-in-a-Row Game
- **Control:** Players use the keypad to navigate and drop game pieces.
- **Gameplay:** The goal is to align four consecutive pieces horizontally, vertically, or diagonally.
- **Graphics:** The game grid and dynamic piece placements are rendered on the GLCD.

## 📜 Results & Achievements
- Successfully developed a **working prototype** of a retro game console.
- Implemented two engaging games—**Snake Game** and **4-in-a-Row Game**—in 8051 Assembly.
- Demonstrated real-time **graphics rendering** on a **128x64 GLCD**.
- Overcame challenges related to limited memory and processing power.

## 📌 Challenges Encountered
- **Memory Constraints:** Efficiently managing limited RAM for game logic and graphics.
- **Collision & Input Handling:** Implementing reliable game mechanics in low-level assembly.
- **Game Physics:** Balancing the mechanics within the constraints of the hardware.

## 🏆 Conclusion
This project showcases how classic gaming concepts can be reimagined on minimal hardware. By merging the fundamentals of assembly programming with creative game design, the G-Yantra Project demonstrates the potential of 8051 microcontrollers for retro gaming and embedded system innovations.

## 🤝 Developed By
- **Rudra Joshi** 
- **Tanvi Shah** 

## 🔗 Repository Structure
📂 G-Yantra-8051_GameBoy_Replica
 
 ├── 📁 Code/           # Assembly Code Files

 ├── 📁 Schematics/     # Circuit Designs & Proteus Files

 ├── 📁 Documentation/  # Project Report & Technical Details
 
 ├── 📁 Images/         # Screenshots & Demos
 
 ├── README.md         # Project Overview and Details

