# Pathfinding with A* Algorithm 🚀  

## **Overview**  
This project implements the **A* (A-Star) algorithm** to find the **shortest and most efficient path** from a given **starting position** to a **goal**, while avoiding obstacles. The algorithm is widely used in **robotics, game development, AI navigation, and GPS systems**.

## **How It Works**  
The A* algorithm calculates the best path using two key factors:  
1. **g(n):** The cost to move from the starting position to the current position.  
2. **h(n):** The estimated cost from the current position to the goal (heuristic).  

It selects the path with the **lowest total cost** (`f(n) = g(n) + h(n)`) to efficiently reach the goal.  

## **Features**  
✅ Finds the shortest path efficiently  
✅ Avoids obstacles (`X`) while navigating  
✅ Uses the **Manhattan Distance heuristic** for better performance  
✅ Accepts user input for grid size and layout  
✅ Provides a **visual representation** of the best path  

## **Installation & Setup**  
To run the project, follow these steps:  

### **1️⃣ Install Python**  
Ensure you have **Python 3.x** installed. If not, download it from [Python’s official site](https://www.python.org/).  

### **2️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/pathfinding-a-star.git
cd pathfinding-a-star
