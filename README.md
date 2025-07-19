# FlappyBird
# Flappy Bird (Java)

A desktop version of Flappy Bird built in Java using Swing and AWT.

---

---

## 🛠 Features

- **Core Gameplay**: Click or press **Space** to flap the bird and navigate through moving pipes.
- **Score Tracking**: Earn 1 point for every pipe successfully passed.
- **Collision Detection**: Game ends when the bird hits a pipe or the ground.

Examples in open‑source Swing implementations like this one show these core components used: game loop, rendering with `JPanel`, `JFrame`, and collision detection via rectangles :contentReference[oaicite:1]{index=1}.

---

## 🧩 Tech Stack

- **Java SE** (tested with JDK 8+)
- **Swing** (`JFrame`, `JPanel`) and **AWT** (`Graphics`, `ImageIcon`)
- Recommended IDE: IntelliJ IDEA, Eclipse, or VSCode

---

## 🚀 Setup & Run

Clone and run with JDK installed:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
javac -d bin src/*.java
java -cp bin Main     # or whichever class contains your main()
