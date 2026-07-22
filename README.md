# 🚗 Navigation Route Planner

A full-stack graph-based navigation application that helps users find routes between cities using **Breadth First Search (BFS)** and **Depth First Search (DFS)** algorithms. The system allows users to create a network of cities and roads, visualize the graph, and find the most efficient route between locations.

---

## 📌 Project Overview

Navigation Route Planner is designed to demonstrate the practical application of **Graph Data Structures**, **BFS**, and **DFS** in route planning systems. Users can manage cities, create road connections, and analyze routes through an interactive web interface.

---

## ✨ Features

### 🔐 Authentication

* User Registration
* User Login
* JWT Authentication
* Protected Routes

### 🏙️ City Management

* Add New Cities
* Update Existing Cities
* Delete Cities
* View All Cities

### 🛣️ Route Management

* Connect Cities with Roads
* Assign Distances
* Edit Road Connections
* Delete Routes

### 🧭 Route Finder

* Select Source City
* Select Destination City
* Find Path using BFS
* Find Path using DFS
* Display Route Path
* Show Total Distance
* Display Traversal Order

### 📊 Graph Visualization

* Interactive Graph View
* City Nodes
* Road Edges
* Zoom and Pan Support
* Path Highlighting

### 📈 Analytics Dashboard

* BFS vs DFS Comparison
* Nodes Visited
* Traversal Statistics
* Route Analysis

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* React Router
* Axios
* React Flow

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

### Algorithms

* Graph Data Structure
* Breadth First Search (BFS)
* Depth First Search (DFS)
* Adjacency List Representation

---

## 📂 Project Structure

```bash
navigation-route-planner/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   └── App.jsx
│   │
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
└── README.md
```

## 🚀 Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/navigation-route-planner.git
cd navigation-route-planner
```

### 2. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 3. Install Backend Dependencies

```bash
cd ../backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend directory:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 5. Run Backend

```bash
npm run dev
```

### 6. Run Frontend

```bash
cd ../frontend
npm run dev
```

---

## 🧠 Algorithm Implementation

### Breadth First Search (BFS)

* Uses Queue Data Structure
* Explores nodes level by level
* Finds the shortest path in an unweighted graph

### Depth First Search (DFS)

* Uses Stack or Recursion
* Explores one branch completely before backtracking
* Useful for graph traversal and path discovery

---

## 📚 Learning Outcomes

This project demonstrates:

* Graph Data Structures
* BFS and DFS Algorithms
* STL Queue Concepts
* Full-Stack Web Development
* REST API Development
* MongoDB Integration
* Authentication & Authorization
* Interactive Data Visualization

---

## 🎯 Future Enhancements

* Dijkstra’s Algorithm
* A* Pathfinding
* Real-Time Maps Integration
* Multi-User Collaboration
* Route Optimization Analytics
* Location-Based Services

---

## 👨‍💻 Author

Developed as a Data Structures and Algorithms based Full-Stack Project to demonstrate graph traversal, shortest path finding, and modern web application development.

⭐ If you found this project useful, consider giving it a star!
