# PathFinderX 🚀

**PathFinderX** is a C++ console-based application that demonstrates pathfinding in a maze using the **Backtracking Algorithm**. It visualizes the steps taken by a "rat" to move from the top-left corner to the bottom-right corner of a 2D maze grid.

---

## 📌 Features

- Solves mazes using backtracking.
- Displays the path from start to destination.
- Easy to customize the maze input.
- Well-structured and beginner-friendly code.

---

## 🔧 Technologies Used

- **C++**
- Standard Template Library (STL)

---


## ✅ How It Works

- `1` represents a valid path.
- `0` represents a wall or blocked cell.
- The rat can only move **right** or **down**.
- The solution is printed as a matrix with `1`s marking the valid path.

---

## ▶️ Sample Maze Input

```cpp
vector<vector<int>> maze = {
    {1, 0, 0, 0},
    {1, 1, 0, 1},
    {0, 1, 0, 0},
    {1, 1, 1, 1}
};
💡 Future Enhancements
Allow diagonal and left/up movements.
Add support for loading maze from a file.
Implement path visualization using graphics (SFML/OpenGL).
Add options for all possible paths or shortest path.


---

Let me know if your code has additional features (like multiple path outputs, graphical UI, or file I/O) — I can customize this README further.


