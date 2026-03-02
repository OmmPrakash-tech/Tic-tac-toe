

🎮 Tic Tac Toe – React Game

A modern and interactive Tic Tac Toe game built using React.js with a clean dark UI, animated effects, and real-time game logic.

This project demonstrates core React concepts like state management, component-based architecture, conditional rendering, and event handling while creating a fun playable game.

✨ Features

✔️ Two-player gameplay (X vs O)
✔️ Current turn indicator
✔️ Win detection logic
✔️ Draw detection
✔️ Live scoreboard (X wins / O wins / Draws)
✔️ New Game button
✔️ Reset Scores functionality
✔️ Modern dark neon UI design
✔️ Responsive layout

🖥️ Preview

Clean neon-themed interface

Interactive grid cells

Dynamic score tracking

Smooth gameplay experience

🛠️ Tech Stack

React.js

JavaScript (ES6+)

CSS3 / Custom Styling

Vite (for fast development build)

📂 Project Structure (Typical)
tic-tac-toe/ <br>
│<br>
├── src/ <br>
│   ├── components/<br>
│   │   ├── Board.jsx<br>
│   │   ├── Square.jsx<br>
│   │   └── ScoreBoard.jsx<br>
│   │<br>
│   ├── App.jsx<br>
│   ├── main.jsx<br>
│   └── styles.css<br>
│<br>
├── public/<br>
├── package.json<br>
└── README.md<br>
⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/tic-tac-toe-react.git

Go to project directory:

cd tic-tac-toe-react

Install dependencies:

npm install

Run development server:

npm run dev

Open in browser:

http://localhost:5173
🧠 Game Logic Overview

The game works using React state:

Board stored as an array of 9 cells

Current player toggles between X and O

Winning combinations are checked after every move

Game stops when:

A player wins

All cells are filled (draw)

Winning Pattern Example
const winningPatterns = [
  [0,1,2],
  [3,4,5],
  [6,7,8],
  [0,3,6],
  [1,4,7],
  [2,5,8],
  [0,4,8],
  [2,4,6]
];
🚀 Future Improvements

🤖 AI opponent (Minimax algorithm)

🔊 Sound effects

🎉 Win animations

🌐 Online multiplayer

📱 Enhanced mobile responsiveness

📚 Learning Outcomes

This project helped practice:

React hooks (useState)

Component reusability

State lifting

Conditional rendering

UI design & styling

Game logic implementation

🤝 Contributing

Contributions are welcome!
Feel free to fork the project and submit pull requests.
