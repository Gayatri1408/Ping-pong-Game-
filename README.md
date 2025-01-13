# Multiplayer Ping Pong Game

A real-time multiplayer ping pong game where two players can control paddles using different browsers. The game features scoring, bouncing ball mechanics, and randomly placed obstacles.

## Features

- Two-player functionality with real-time updates across browsers.
- Players control paddles using keyboard input:
  - Player 1 (Red Paddle): \`W\` (up), \`S\` (down).
  - Player 2 (Blue Paddle): \`Arrow Up\`, \`Arrow Down\`.
- Ball bounces off the paddles and the walls.
- Randomly positioned square obstacles that bounce the ball on collision.
- Scoring system: Players score points when the ball goes out of bounds on the opponent's side.
- Game starts when a player clicks the **Start** button.

---

## Setup Instructions

### Prerequisites
- Python 3.x installed
- Flask installed (\`pip install flask\`)
- Flask-SocketIO installed (\`pip install flask-socketio\`)

### Project Structure
Ensure the project is structured as follows:

\`\`\`
ping-pong-game/
├── app.py
├── static/
│   ├── style.css
│   └── game.js
├── templates/
│   └── index.html
└── README.md
\`\`\`

### Installation

1. Install the required Python dependencies:
   \`\`\`bash
   pip install flask flask-socketio
   \`\`\`

2. Run the Flask server:
   \`\`\`bash
   python app.py
   \`\`\`

3. Open a web browser and navigate to:
   \`\`\`
   http://127.0.0.1:5000/
   \`\`\`

4. Open another browser or incognito mode, and navigate to the same URL to play as Player 2.

---

## Technical Choices

- **Flask + Flask-SocketIO**: For real-time communication between the server and multiple clients.
- **HTML, CSS, JavaScript**: To create an interactive frontend for the game.
- **WebSocket**: For low-latency, real-time communication to sync game state across players.
- **Python**: Simplified backend logic for handling game mechanics and communication.

---

## Known Limitations

- Obstacles are placed randomly but do not update mid-game.
- Ball speed and paddle movement are not configurable.
- No support for mobile devices due to keyboard-based controls.
- Limited error handling for edge cases like network interruptions.

---

## Future Improvements

- Add support for AI-based single-player mode.
- Improve responsiveness for mobile and tablet devices.
- Enhance obstacle logic to include dynamic movement.
- Add sound effects and animations.


