# 🎮 Tower Defense Game  
**Object-Oriented Programming Project**  
**Language:** C++  
**University:** Ho Chi Minh City University of Science  
**Lecturer:** TRƯƠNG TOÀN THỊNH

---

## 1. 📘 Introduction

This project is designed to help students apply basic programming techniques, data structures, and **object-oriented programming (OOP)** concepts to build a simple **Tower Defense** game using **C++**.

### 📚 Required Knowledge:
- File I/O operations
- Control flow and process logic
- Data structures (e.g., arrays, lists, queues)
- Object-oriented programming (classes, inheritance, polymorphism, etc.)

Students are expected to conduct additional research to complete the game and enhance its functionality.

---

## 2. 🧩 Game Scenario

- At the start, the game presents a **map** and a **configuration table** for the player to input initial parameters.
- After setup, the game runs **automatically**, and the player observes the battle.
- The game ends when:
  - All enemies are destroyed ✅
  - An enemy reaches the finish line ❌

### 🎮 After the Game Ends:
- Press `'y'` → Restart game with initial settings
- Press any other key → Exit game

### 🚩 Progressing Through Levels:
- Defeating all enemies advances the player to the **next level**.
- Each level increases in difficulty (e.g., more enemies, stronger resistance).
- Reaching a certain level is considered a **victory**, otherwise the game restarts.

---

## 3. ✅ Project Requirements

### 🔫 Collision Handling
- Implement **bullet-enemy collision detection**
- Add **visual effects** for more engaging gameplay

### 💾 Save & Load Functionality
- Allow users to **save the game state**
- Implement loading of **saved games**

### 🗺 Pre-game Interface
- Before the game starts, display:
  - The **map**
  - Tower **buildable zones**
  - Enemy **paths**
- Let players **analyze** and **choose parameters** strategically

### 🧱 Multiple Levels
- Create at least **4 levels**, each with:
  - A **unique map**
  - Increasing difficulty (e.g., enemy speed, quantity)

### 🧭 Game Menu
- Implement a menu with options:
  - `New Game`
  - `Load Game`
  - `Settings`

- Add **audio support**:
  - Background music
  - Game sound effects
- Include **on/off toggle** for both types of sound

### 🌟 Team-Specific Special Feature
- Each group must design a **unique feature** that is not shared with other teams.
- This feature should **enhance gameplay** and **distinguish** your version of the game.

---

## 🔧 Suggestions for Implementation
- Use OOP to define classes like `Tower`, `Enemy`, `Bullet`, `Map`, and `GameManager`
- Consider using **STL containers** such as `vector`, `queue`, and `map`
- Modularize code into different files for scalability
- Design reusable functions and follow clean coding practices

---

## 🎯 Final Note

This project encourages creativity and teamwork. Students should focus on both **functionality** and **user experience** to deliver a polished game.

Good luck and enjoy coding your Tower Defense game!

---
