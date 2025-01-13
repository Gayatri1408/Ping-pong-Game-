# Multiplayer Ping Pong Game

A real-time multiplayer ping pong game where two players can control paddles using different browsers. The game features scoring, bouncing ball mechanics, and randomly placed obstacles.

## Features

- Two-player functionality with real-time updates across browsers.
- Players control paddles using keyboard input:
  - Player 1 (Red Paddle): `W` (up), `S` (down).
  - Player 2 (Blue Paddle): `Arrow Up`, `Arrow Down`.
- Ball bounces off the paddles and the walls.
- Randomly positioned square obstacles that bounce the ball on collision.
- Scoring system: Players score points when the ball goes out of bounds on the opponent's side.
- Game starts when a player clicks the **Start** button.

---

## Setup Instructions

### Prerequisites
- Python 3.x installed
- Flask installed (`pip install flask`)
- Flask-SocketIO installed (`pip install flask-socketio`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ping-pong-game.git
   cd ping-pong-game
