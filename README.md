# Copycube (Replicube Web)

A web-based recreation of the puzzle game **Replicube**.
This project aims to bring the experience of spatial reasoning and pattern matching to the browser using modern web technologies.

## 🎮 Demo

[Watch the Demo Video](demo.mp4)

> *Check out `demo.mp4` in the repository if the video doesn't play.*

## 🕹️ Gameplay

The goal is to replicate the "Reference Object" by writing Python code.

1.  **Analyze**: Look at the target shape in the right-hand panel.
2.  **Code**: Use the **Ace Editor** (left panel) to write a Python `main(x, y, z)` function.
    *   Return a color string (e.g., `'RED'`, `'BLUE'`) to place a voxel.
    *   Return `None` or `'EMPTY'` to leave the space empty.
3.  **Run**: Click "RUN CODE" to execute your logic.
4.  **Verify**: The specific "Player View" will update. The system calculates a **Shape Match** and **Overall Match** score.
5.  **Win**: Achieve 100% accuracy!

## 🛠️ Technology Stack

*   **[Three.js](https://threejs.org/)**: For high-performance 3D rendering of the voxel grid.
*   **[Pyodide](https://pyodide.org/)**: To execute the user's Python code directly in the browser (WebAssembly).
*   **[Ace Editor](https://ace.c9.io/)**: For a robust code editing experience with syntax highlighting.
*   **Vanilla HTML/CSS/JS**: Core application logic and "Dark Industrial" styling.

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/gabrieleiannace/Copycube.git
    ```
2.  Open `index.html` in your web browser.
    *   *Note*: For the best experience (and to avoid CORS issues with cross-origin worker loading in some browsers), it is recommended to use a local development server.
    *   Example with Python:
        ```bash
        python -m http.server
        ```
    *   Then visit `http://localhost:8000`.

## 📜 License

Project created for educational/entertainment purposes.
