Escape Road - Web Game Project
A dynamic, web-based runner game featuring two distinct implementations: a high-performance **Unity WebGL build** and a lightweight, custom **JavaScript Canvas** engine.

Overview:
Escape Road is a side-scrolling survival game where the player must navigate through obstacles while collecting power-ups to achieve the highest score possible. The project demonstrates the integration of heavy game engines (Unity) alongside native web technologies (HTML5/JS).
Features

* **Dynamic Gameplay**: Fast-paced side-scrolling action with increasing difficulty over time.
* **Power-up System**: Includes **Shields** for protection and **Time Slow** mechanics to navigate tight spots.
* **Parallax Backgrounds**: Multi-layered background scrolling to create a sense of depth and immersion.
* **Unity WebGL Integration**: A fully responsive wrapper to run high-quality Unity games directly in the browser.
* **Responsive Design**: Optimized for both Desktop and Mobile browsers with automatic scaling.

## Tech Stack

* **Frontend**: HTML5, CSS3 (Dark Theme)
* **Game Engine 1**: Unity WebGL (WebAssembly & JavaScript)
* **Game Engine 2**: Native JavaScript Canvas API (for the lightweight version)
* **Physics**: Custom-built gravity and collision detection logic in Vanilla JS.

## Project Structure

* `.html`: The entry point of the game. It sets up the Unity loader, manages the loading screen/progress bar, and handles the canvas rendering.
* `.js`: The core logic for the 2D version. Contains classes for `Player`, `Obstacle`, and `PowerUp`, as well as the main `gameLoop`.
* `style.css`: Provides the layout and "Dark Mode" styling for the game container.

## How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/escape-road.git
```
2. Open the `.html` file in any modern web browser (Chrome, Firefox, or Edge).
3. Use the **Spacebar** or **Click** to jump/interact with the game.

## 📈 Future Improvements

* [ ] Add a Global Leaderboard using Firebase.
* [ ] Implement more diverse obstacle patterns.
* [ ] Add sound effects and background music.

---

### Tips for your GitHub upload:

1. **Rename the files**: GitHub usually expects your main file to be named `index.html`. If you rename your `.html` file to `index.html`, GitHub Pages will be able to host your game for free.
2. **Add a Screenshot**: Take a screenshot of the game and save it as `screenshot.png` in your folder, then link it in the README.
3. **License**: Since you are sharing code, consider adding a `LICENSE` file (like MIT License) so others know how they can use your code.
