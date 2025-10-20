#  Degrees of Separation — BFS Search

This project implements a **Breadth-First Search (BFS)** algorithm to find the shortest connection between two actors based on the movies they have starred in together.  
It is inspired by the famous *“Six Degrees of Kevin Bacon”* problem.

---

##  Description :)

The program builds a graph where:
- **Nodes** represent actors.
- **Edges** connect actors who appeared in the same movie.

Using BFS, the algorithm finds the **shortest path** (smallest number of movies) connecting two given actors.

---

##  Project Structure
```
├── degrees.py # Main program (core BFS logic)
├── util.py # Contains Node, StackFrontier, and QueueFrontier classes
├── Data/
│ ├── people.csv # List of actors (id, name, birth)
│ ├── movies.csv # List of movies (id, title, year)
│ └── stars.csv # Actor-movie relations
└── README.md
```
---

## Requirements

- Python **3.8+**
- No external libraries are required (only built-in modules: `csv`, `sys`)

