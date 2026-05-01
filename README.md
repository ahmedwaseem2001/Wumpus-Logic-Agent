
# Wumpus World Agent

A full-stack web application that simulates the classic AI **Wumpus World** problem[cite: 2]. The project consists of a React-based frontend for visualizing the grid and interacting with the agent, and an Express/Node.js backend for managing the game state, logic, and generating percepts[cite: 2].

---

## 📋 Table of Contents
- [Features](#features)[cite: 2]
- [Technologies Used](#technologies-used)[cite: 2]
- [Project Structure](#project-structure)[cite: 2]
- [Installation and Setup](#installation-and-setup)[cite: 2]
- [API Endpoints](#api-endpoints)[cite: 2]
- [How to Play](#how-to-play)[cite: 2]
- [Future Improvements](#future-improvements)[cite: 2]

---

## ✨ Features
*   **Dynamic Grid Setup**: Start the game with customizable grid dimensions (rows and columns)[cite: 2].
*   **Backend-Driven Logic**: The game state (Wumpus, pits, gold, agent) is securely managed on the server[cite: 2].
*   **Percepts Simulation**: Generates percepts dynamically (e.g., *Stench* for Wumpus, *Breeze* for Pits)[cite: 2].
*   **Basic Inference Engine**: Performs backend safety checks before allowing agent moves[cite: 2].
*   **Goal Checking**: Automatically detects if the agent has reached the gold to trigger a win[cite: 2].
*   **Interactive UI**: Responsive React interface showing grid, percepts, and inference steps[cite: 2].

---

## 🛠️ Technologies Used
*   **Frontend**: React.js, HTML5, CSS3[cite: 2]
*   **Backend**: Node.js, Express.js[cite: 2]
*   **Middleware**: CORS[cite: 2]

---

## 📂 Project Structure
```text
wumpus-agent/
│
├── backend/
│   ├── package.json
│   └── server.js         # Express server, game logic, state management
│
└── frontend/
    ├── package.json
    ├── public/
    └── src/
        ├── App.js        # Main React component, state & API calls
        ├── Grid.js       # UI component for rendering the Wumpus grid
        ├── index.js      # React entry point
        └── styles.css    # Application styling
```
[cite: 2]

---

## 🚀 Installation and Setup

### Prerequisites
Make sure you have **Node.js** installed on your machine[cite: 2].

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd "wumpus agent"
```
[cite: 2]

### 2. Setup the Backend
Open a terminal, navigate to the backend directory, install dependencies, and start the server[cite: 2].
```bash
cd backend
npm install
node server.js
```
[cite: 2]
*Backend running on: http://localhost:3000*[cite: 2]

### 3. Setup the Frontend
Open a new terminal, navigate to the frontend directory, install dependencies, and start the React application[cite: 2].
```bash
cd frontend
npm install
npm start
```
[cite: 2]
> **Note**: If prompted to run on a different port (e.g., 3001), type **Y** to accept[cite: 2].

---

## 🔌 API Endpoints
*   **`POST /init`**: Initializes a new game grid[cite: 2].
    *   *Body*: `{ "rows": 4, "cols": 4 }`[cite: 2]
*   **`GET /state`**: Retrieves the current agent and environment state[cite: 2].
*   **`POST /move`**: Attempts to move the agent to specific coordinates `{ x, y }`[cite: 2].

---

## 🎮 How to Play
1. Launch both backend and frontend servers[cite: 2].
2. Specify grid dimensions in the web interface[cite: 2].
3. Click **Start** to initialize[cite: 2].
4. Click adjacent cells to move the agent (**A**)[cite: 2].
5. Use **Percepts** (Breeze, Stench) to avoid hazards[cite: 2].
6. Find the **Gold (G)** to win![cite: 2]

---

## 🔮 Future Improvements
*   **Advanced AI Agent**: Implement automated Propositional Logic solvers[cite: 2].
*   **Visual Enhancements**: Add rich graphics/icons for game entities[cite: 2].
*   **Scoring System**: Introduce points and arrow-shooting mechanics[cite: 2].
*   **Fog of War**: Hide unvisited cells for authentic exploration[cite: 2].
```


3.  Niche **"Commit changes"** par click karein.
4.  Aapka project ab professional nazar aaye ga! Isme aapka **package-lock.json**[cite: 1, 2] aur **wumpus agent report.docx**[cite: 3] bhi background mein properly linked rahen ge.
