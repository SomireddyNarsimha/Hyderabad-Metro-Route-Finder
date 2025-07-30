# 🚇 Hyderabad Metro Route Finder

A smart Java-based metro routing system to find the **shortest, cheapest, and most efficient route** between any two metro stations in the Hyderabad Metro network.

---

## 📌 Features

- 🛤️ Calculates optimal routes across **Red**, **Blue**, and **Green** lines.
- 🔁 Detects and includes **interchange stations** when switching lines.
- 🧮 Provides **fare estimation** based on official fare slabs.
- ⏱️ Estimates **travel duration** and suggests **first/last train timings**.
- 🗺️ Easy-to-update graph-based metro map for future station expansions.

---

## 🧠 How It Works

- The metro network is modeled as a **graph** (stations as nodes, connections as edges).
- The **shortest route** is calculated using **Dijkstra’s Algorithm** or a similar pathfinding method.
- Routes that involve line changes are handled by identifying **interchange stations**.
- Fare calculation is based on the number of stations or total distance traveled.

---

## 🏗️ Tech Stack

| Layer        | Tech             |
|--------------|------------------|
| Language     | Java             |
| Logic        | Graph Theory, Dijkstra’s Algorithm |


---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/SomireddyNarsimha/Hyderabad-Metro-Route-Finder.git
   cd Hyderabad-Metro-Route-Finder
