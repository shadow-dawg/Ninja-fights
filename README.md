# Ninja Fights

Ninja Fights is a retro-style 2D fighting game built with JavaScript and the HTML5 Canvas. Face off against a friend in a local two-player battle featuring unique characters, classic pixel art animations, and fast-paced combat.

## Features

*   **Local 2-Player Combat:** Challenge a friend on the same keyboard.
*   **Two Unique Fighters:** Play as the swift Samurai Mack or the powerful Kenji, each with a full set of animations.
*   **Dynamic Animations:** Characters have sprites for idling, running, jumping, attacking, taking damage, and dying.
*   **Classic Fighting Mechanics:** A timed match with health bars, hit detection, and a winner declaration.
*   **Retro Aesthetics:** Features pixel art graphics and background music to set the mood.
*   **Responsive Canvas:** The game canvas adapts to the viewport size for a full-screen experience.

## How to Play

1.  Open `home.html` to see the main menu.
2.  Click `▶ Play 2 Player` to start the game.
3.  Use the controls below to move, jump, and attack.
4.  The first player to deplete the opponent's health bar wins.
5.  If the timer runs out, the player with the most health is declared the winner.

## Controls

| Action      | Player 1 (Samurai Mack) | Player 2 (Kenji)       |
|-------------|-------------------------|------------------------|
| **Move Left** | `A`                     | `←` (Left Arrow)       |
| **Move Right**| `D`                     | `→` (Right Arrow)      |
| **Jump**      | `W`                     | `↑` (Up Arrow)         |
| **Attack**    | `Spacebar`              | `↓` (Down Arrow)       |

You can also mute/unmute the background music using the button in the top-right corner of the game screen.

## Running Locally

No complex setup is required to run this game.

1.  Clone the repository:
    ```bash
    git clone https://github.com/shadow-dawg/ninja-fights.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd ninja-fights
    ```
3.  Open the `home.html` file in your web browser.

## Project Structure

The project is organized to separate logic, assets, and views.

```
/
├── home.html         # The main menu screen
├── index.html        # The main game arena and UI layout
├── index.js          # Core game loop, event listeners, and initialization
├── js/
│   ├── classes.js    # Defines the Fighter and Sprite classes
│   └── utils.js      # Helper functions for collision, timer, and winner logic
├── img/              # Contains all image assets and character sprites
└── sounds/           # Contains game audio files
```

## Built With

*   **HTML5:** Used for the structure and Canvas API.
*   **CSS3:** For styling the UI elements like health bars and menus.
*   **JavaScript (ES6):** Powers all game logic, character control, and rendering.
