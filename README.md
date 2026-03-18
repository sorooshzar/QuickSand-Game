# QuickSand-Game
QuickSand: “The harder you struggle, the harder it is to escape” is an interactive, single-player desktop game built in Python using Pygame where a player navigates desert-themed escape rooms filled with traps, moving hazards, and quicksand.
# QuickSand 🎮
**"The harder you struggle, the harder it is to escape."**

## 🧠 Overview
QuickSand is an adaptive difficulty platformer game built in Python using Pygame. The game dynamically adjusts its difficulty based on player performance in real time, creating a personalized challenge for each player.

This project was developed for a high school science fair and investigates how behavior-based adaptive systems impact player performance and engagement.

---

## ❓ Research Question
Does a behavior-based adaptive difficulty system improve player performance and engagement compared to a static difficulty system?

---

## 🎮 Game Description
Players navigate through desert-themed escape rooms filled with hazards such as quicksand, moving platforms, and enemies. The goal is to reach the exit while the game continuously monitors performance and adjusts difficulty.

---

## ⚙️ Adaptive System
The game calculates a **Skill Score** based on:
- Reaction time
- Completion speed
- Number of mistakes
- Retry frequency

Difficulty changes in real-time:
- Better performance → harder game
- More struggle → more punishing mechanics

---

## 🧪 Experiment
Two modes are tested:
1. Static difficulty
2. Adaptive difficulty

Data collected:
- Completion time
- Number of deaths
- Success rate
- Player enjoyment rating

---

## 🛠️ Tech Stack
- Python
- Pygame
- CSV (data logging)

---

## 👥 Team Roles
- Game Development
- Adaptive System Engineering
- UI/Design
- Data & Analysis

---

## 🚀 How to Run
```bash
pip install pygame
python main.py
