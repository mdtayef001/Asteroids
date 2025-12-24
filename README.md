# 🚀 Asteroids Game (Pygame)

A classic **Asteroids-style arcade game** built using **Python and Pygame**. Control a spaceship, shoot incoming asteroids, and survive as long as you can! Large asteroids split into smaller, faster ones when destroyed, increasing the challenge.

---

## 🎮 Game Overview

In this game, the player controls a spaceship placed at the center of the screen. Asteroids spawn and move across space. The player must shoot asteroids to destroy them while avoiding collisions.

### Core Mechanics

* Large asteroids split into **two smaller asteroids** when shot
* Smaller asteroids move **faster** than larger ones
* The game ends when the player collides with an asteroid

---

## 🛠️ Technologies Used

* **Python 3**
* **Pygame** (game loop, rendering, events, collision detection)

---

## 📦 Project Structure

```
.
├── main.py              # Game entry point
├── player.py            # Player spaceship logic
├── asteroid.py          # Asteroid behavior and movement
├── asteroidfield.py     # Asteroid spawning system
├── shot.py              # Bullet / shooting logic
├── constants.py         # Game constants (screen size, speeds, radius)
├── logger.py            # Event and state logging
└── README.md            # Project documentation
```

---

## 🎯 Features

* Smooth spaceship movement
* Shooting mechanics with cooldown
* Asteroid collision detection
* Asteroid splitting system
* Event logging for debugging
* Object-oriented design

---

## 🧠 Game Logic Highlights

* **Collision Detection** using `pygame.sprite`
* **Asteroid Splitting** using vector rotation
* **Dynamic Difficulty** as asteroids get smaller and faster
* **Frame-independent movement** using delta time (`dt`)

---

## ▶️ How to Run the Game

1. Make sure Python 3 is installed
2. Install Pygame:

```bash
pip install pygame
```

3. Run the game:

```bash
python main.py
```

---

## 🕹️ Controls

* **WASD** → Move the spaceship
* **Spacebar** → Shoot

---

## ❌ Game Over Condition

* The game ends when the player collides with any asteroid

---

## 📌 Future Improvements

* Score system
* Sound effects and background music
* Particle explosions
* Lives and restart system
* Power-ups

---

## 👨‍💻 Author

**Tayef Hossain Nabil**
Web Developer | Python & Pygame Enthusiast

* 🌐 Boot.dev Profile: [https://www.boot.dev/u/mdtayef](https://www.boot.dev/u/mdtayef)

---

## 📚 Learning Source

This project was built as part of my learning journey on **[Boot.dev](https://www.boot.dev/)**, where I practiced:

* Object-Oriented Programming (OOP)
* Game loops and real-time updates
* Collision detection
* Clean project structure
