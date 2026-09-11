# Match Maker 🧩

A **2D memory-matching (pairs) game** built with **Godot Engine** using **GDScript**.
Flip tiles, find matching pairs, and clear the board in as few moves as possible.

![Screenshot](https://github.com/user-attachments/assets/03f78314-009b-4138-bb73-b2f909661e0a)

---

## 🚀 Features

* Classic **tile-flip memory matching** gameplay
* **4 difficulty levels** — 2×2, 4×4, 6×6, and 8×8 grids
* Move counter, pairs-found counter, and elapsed-time tracking
* Level select lobby and game-over summary screen

---

## 🧠 Built With

| Technology        | Purpose                |
| ----------------- | ---------------------- |
| **Godot Engine**  | Game engine            |
| **GDScript**      | Core game logic        |
| **Scenes**        | Modular game structure |
| **Singletons**    | Game/image/signal management |
| **Assets folder** | Sprites & images       |

---

## ▶️ How to Play

1. **Open in Godot Engine**

   * Open the project folder in Godot.
2. **Run the main scene**

   * Press **Play** to start.
3. **Controls**

   * Select a level from the lobby
   * Click tiles to flip and match pairs
   * Clear all pairs to finish the level

---

## 🗂 Project Structure

```
match-maker/
├── Assets/
├── Scenes/
├── Script/
├── Singletons/
├── icon.svg
├── project.godot
├── .gitignore
└── LICENSE
```

* **Assets/** – Graphics & images
* **Scenes/** – Godot scenes (levels, objects)
* **Script/** – Game logic in GDScript
* **Singletons/** – Autoload managers (game state, images, signals)
