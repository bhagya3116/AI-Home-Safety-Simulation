# AI-Home-Safety-Simulation
AI Home Safety Simulation using Python and Pygame. Includes fire spread, intruder movement, and BFS pathfinding. Shows real-time escape routes and danger alerts. Interactive grid where the user controls the resident. Great for learning AI movement and emergency simulations.

📌 Overview

This simulation models a home environment where both fire and an intruder pose threats to the resident.
Using AI pathfinding (BFS), the system continuously calculates the safest escape path toward the exit while hazards spread or move.
Interactive controls, automated danger detection, and real-time visual feedback make this an effective demonstration of emergency response modeling and intelligent decision-making in dynamic environments.


🚀 Features

🔥 Dynamic Fire Spread – expands unpredictably across the grid.

🧨 Intruder AI – uses BFS to chase the resident.

🧭 BFS Pathfinding – calculates shortest escape route in real time.

⚠️ Danger Alerts – notifies when fire or intruder is near.

🎮 Interactive Controls – move resident & trigger emergency alerts.


🧠 Technologies Used

Python

Pygame

Breadth-First Search (BFS)

Grid-based environment

Randomized hazard simulation


🔧 Installation

Install pygame:

pip install pygame


Run the simulation:

python main.py

🎮 Controls
Key	Action
⬆⬇⬅➡	Move resident
E	Send emergency alert
Mouse Click	Add fire to that cell
📁 Project Structure
.
├── main.py
└── README.md


📝 How It Works

A 20×20 grid models the home interior.

Fire spreads stochastically to neighboring cells.

Intruder uses BFS to move closer each frame.

BFS computes the shortest safe path to the exit.

Danger is detected within adjacent cells.

Simulation ends when:

Resident escapes

Resident is caught

Resident reaches fire


🎯 Purpose

This project demonstrates AI-driven decision-making, real-time pathfinding, and hazard modeling. It is ideal for learning BFS pathfinding, game logic, simulation design, and emergency-response algorithms.


📘 Future Enhancements

A* pathfinding

Smoke simulation

Multi-level maps

Multiple intruders

Sound effects

Fire extinguishers

📄 License

Free to use for learning, research, and academic purposes.
