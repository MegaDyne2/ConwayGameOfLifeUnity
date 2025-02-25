# Conway's Game of Life - Unity Version

## Overview
This is a Unity-based interactive implementation of **Conway’s Game of Life**, a classic zero-player game that demonstrates emergent behavior through cellular automata. Users can create and manipulate grids of varying sizes, populate them with predefined patterns, and control the evolution of generations either manually or through an automated timer.

---

## Features

### Grid Customization
- **Board Size**: Adjustable width and height from **8x8 to 50x50**.
- **Cell Size**: Can be adjusted dynamically between **25 to 99 pixels** for better visibility and interaction.

### Board Initialization
- **Build Board**: Generates a grid of cells based on user-defined dimensions.
- **Fill Board With Patterns**:
  - **True Random** – Randomly assigns live and dead cells.
  - **Test Random** – Predefined deterministic random pattern.
  - **Blinker** – A three-cell oscillator.
  - **Toad** – A period-2 oscillator.
  - **Beacon** – A four-cell block oscillator.
  - **Glider** – A moving pattern that travels across the board.

### Game Controls
- **Manual Generation Advancement**:
  - Click a button to step through generations one at a time.
- **Automated Generation Cycling**:
  - Enable auto-run to progress through generations on a timer.
  - Timer interval adjustable between **0.1 seconds to 3 seconds**.

---

## How to Use
1. **Set Board Dimensions**: Adjust the width and height of the grid (between **8x8** and **50x50**).
2. **Adjust Cell Size**: Modify the cell size (between **25 and 99 pixels**) for better visibility.
3. **Generate the Board**: Click the **Build Board** button to create the grid.
4. **Populate the Board**: Choose from:
   - **True Random**
   - **Test Random**
   - **Blinker**
   - **Toad**
   - **Beacon**
   - **Glider**
5. **Advance Generations**:
   - **Click to manually step forward**.
   - **Enable Auto Next Generation** and set a timer between **0.1s and 3s** to progress automatically.

---

## Future Enhancements
- Implement a save/load feature for custom patterns.
- Add more predefined patterns.
- Improve UI responsiveness for better scalability.

---

### License
This project is open-source. Feel free to modify and expand upon it.

---

### Contact
For any questions or improvements, feel free to reach out!
