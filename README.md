# 🧩 Picture Puzzle Game (Java Swing)

A fun **sliding picture puzzle game** made with **Java Swing GUI**.  
Players can click on tiles to rearrange the pieces of an image and solve the puzzle.

---

## 🎮 Gameplay Overview

- The game shows a 3x3 grid of image pieces.
- One image tile is **blank** (represented by a star icon), allowing adjacent tiles to be moved.
- Click on a tile next to the blank space to slide it into the empty spot.
- Press the **sample image** to change the puzzle to a new picture.
- Solve the puzzle by rearranging all the pieces to match the **sample image**.

---

## 🧱 Technologies Used

- Java
- Java AWT & Swing (`JFrame`, `JButton`, `ImageIcon`, `JLabel`, `ActionListener`)

---

## 🖼️ Puzzle Images

The game includes **three different puzzles**, which cycle when the player clicks the sample image.

Ensure the following images exist in a `pic/` folder relative to your `.java` file:
pic/ ├── 1.jpg to 9.jpg (Puzzle 1 pieces) ├── 11.jpg to 19.jpg (Puzzle 2 pieces) ├── 21.jpg to 29.jpg (Puzzle 3 pieces) ├── main.jpg (Sample image 1) ├── main2.jpg (Sample image 2) ├── main3.jpg (Sample image 3) ├── starB0.jpg (Blank icon for Puzzle 1) ├── starB10.jpg (Blank icon for Puzzle 2) ├── starB20.jpg (Blank icon for Puzzle 3)

---

## 🚀 How to Run

1. Ensure Java is installed on your system.
2. Place all required image files in a folder named `pic` next to your `.java` file.
3. Compile the Java program:
   ```bash
   javac PicturePuzzle.java
Run the game:
java PicturePuzzle

📌 Features
✅ 3x3 Sliding Puzzle Game
✅ Click-based intuitive movement
✅ Multiple puzzles with one click
✅ Visual feedback via icons
✅ Interactive GUI with image-based layout
✅ Rotating image samples to challenge players

✨ Future Improvements

Add shuffle functionality at the start
Timer or move counter to make it competitive
Winning condition checker and congratulatory popup
Improved UI scaling and layout management
