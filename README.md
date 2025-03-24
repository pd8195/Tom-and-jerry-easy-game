This application is a **2D Dungeon Crawler** game built using **HTML, CSS, and JavaScript**, with a simple game loop and basic enemy AI. The goal of the game is for the player (represented by **Jerry**, an image of a character) to **survive as long as possible** while avoiding enemies (**Tom** characters) that chase the player.

### **Features**
- **Player Movement:**  
  - The player can move **up, down, left, and right** using the **arrow keys**.
  - Movement is limited within the **canvas boundaries**.

- **Enemies (Tom) Behavior:**  
  - New enemies spawn **every 5 seconds** at a random position on the canvas, ensuring a minimum safe distance from the player.
  - Enemies move toward the player continuously at a **fixed speed**.

- **Collision Detection:**  
  - If the player collides with any enemy, the game **ends immediately**.

- **Score System:**  
  - The score is measured by **the number of seconds survived**.
  - The current score is displayed on the **scoreboard** above the game canvas.
  - When the game ends, the **final score** is displayed.

- **Game Controls:**  
  - The game starts when the player clicks the **"Start Game" button**.
  - After a game-over event, the player can restart by clicking the button again.

### **UI Elements**
- **Canvas:** The main game area where the player and enemies move.
- **Score Display:** Displays the number of seconds survived.
- **Game Over Screen:** Appears when the player loses, showing the final survival time.
- **Start Button:** Starts or restarts the game.

### **Technology Used**
- **HTML5 Canvas API** for rendering the game.
- **CSS** for styling UI elements like the scoreboard and game-over screen.
- **JavaScript** for handling game logic, animations, player input, and collision detection.

This is a simple but engaging survival-based game with increasing difficulty as more enemies spawn over time.
