# 🐢 Turtle Crossing Game

A Frogger-style arcade game built using Python and the Turtle graphics module.

This project was developed as part of the 100 Days of Code – Python Bootcamp, with a focus on Object-Oriented Programming and multi-file project structure.

---

## 🎮 Game Overview

The player controls a turtle attempting to cross a busy road filled with moving cars.

- Each successful crossing increases the level.
- Cars move faster as the level increases.
- The game ends when the turtle collides with a car.

---

## 🧠 Concepts Applied

This project focuses on:

- Object-Oriented Programming (OOP)
- Class separation and responsibility
- Collision detection
- Game loop logic
- Randomized object spawning
- State management

---

## 🏗 Project Structure

```
turtle-crossing-game/
│
├── main.py
├── player.py
├── car_manager.py
├── scoreboard.py
└── README.md
```

### Responsibilities

- `player.py` → Controls turtle movement and reset logic  
- `car_manager.py` → Handles car spawning, movement, and speed scaling  
- `scoreboard.py` → Manages level display and game over screen  
- `main.py` → Coordinates the game loop and connects all components  

---

## 🚀 Features

- Randomized car spawning
- Increasing difficulty per level
- Clean separation of concerns
- Collision detection using distance calculation
- Responsive keyboard controls

---

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. Clone this repository:

```bash
git clone <your-repo-link>
```

3. Run the game:

```bash
python main.py
```

---

## 📸 Demo

![Game Demo](images/demo_turtlecross.png)
![Game Demo](images/demo2_turtlecross.png)

---

## 📈 What I Learned

This project strengthened my understanding of:

- Structuring multi-file Python applications
- Managing dynamic objects using lists
- Designing scalable class-based systems
- Debugging real-time game behavior

This marks an early step in my journey toward building larger, more complex software systems.