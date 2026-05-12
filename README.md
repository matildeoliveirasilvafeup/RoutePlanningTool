# 🚗 Individual Route Planning Tool

## 📌 Overview
This project was developed as part of the **Design of Algorithms course**.  
It is a route planning system that calculates optimal paths in a weighted graph, supporting multiple constraints and travel modes.

The goal of this project is to demonstrate the application of graph algorithms, pathfinding techniques, and constraint-based optimization in a practical scenario.

---

## ✨ Features
- Computes the shortest path between two nodes in a graph
- Supports multiple routing modes:
  - 🚗 Driving mode
  - 🚗 Driving mode with restrictions
  - 🚶‍♂️ Walking + Driving hybrid mode
- Supports route constraints:
  - Avoid specific nodes
  - Avoid specific road segments
  - Include mandatory nodes in the route
- Batch processing for multiple route queries

---

## ⚙️ Usage

### 🖥️ Menu Mode
1. Place the required CSV files inside the `csv_files/` folder:
   - `Distances.csv`
   - `Locations.csv`
2. Run the program
3. Select one of the available options:
   - Route calculation
   - Batch mode execution
   - Exit program

---

### 📦 Batch Mode
1. Place the CSV files inside `csv_files/`
2. Place `input.txt` inside `Batch_Mode_Files/`
3. Run the program and select **Batch Mode**
4. Results will be generated in:
   - `Batch_Mode_Files/output.txt`

---

## 📄 Input Format (Batch Mode)

Each test case in `input.txt` must follow this structure:

### 🚗 Driving Mode
#TestName

Mode: driving

Source: id

Destination: id

AvoidNodes: id,id,id (optional)

AvoidSegments: (id,id),(id,id) (optional)

IncludeNode: id (optional)

---

### 🚶 Driving + Walking Mode
Mode: driving-walking

Source: id

Destination: id

MaxWalkTime: int

AvoidNodes: id,id,id (optional)

AvoidSegments: (id,id),(id,id) (optional)
---

## 👥 Authors
Developed by **me and my group** as part of the *Design of Algorithms* course.  
This project was completed collaboratively, focusing on graph algorithms, optimization techniques, and structured problem solving.
