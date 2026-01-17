🃏 Blackjack Game (Python)

A simple command-line Blackjack game built using Python.
Play against the computer and experience the classic casino game logic right in your terminal.

📌 Features

🎴 Random card dealing

🧮 Automatic score calculation

🃏 Blackjack detection (Ace + 10)

♠️ Ace adjustment (11 → 1 to avoid bust)

🤖 Smart computer logic (hits until score ≥ 17)

🔁 Option to replay the game

🛠️ Technologies Used

Python 3

random module

Basic game logic & control flow

📂 Project Structure
blackjack-game/
│
├── main.py          # Main game logic
├── art.py           # ASCII logo (used for game branding)
└── README.md        # Project documentation

▶️ How to Run the Game

Make sure Python 3 is installed on your system.

Clone this repository:

git clone https://github.com/your-username/blackjack-game.git


Navigate into the project folder:

cd blackjack-game


Run the game:

python main.py

🎮 How to Play

You and the computer both start with 2 cards

Your goal is to get a score as close to 21 as possible without going over

Card values:

Number cards → face value

Face cards (J, Q, K) → 10

Ace → 11 or 1 (automatically adjusted)

Choose:

'y' → Take another card

'n' → Pass your turn

The computer draws cards until its score reaches 17 or higher

🏆 Winning Rules

Blackjack (21 with 2 cards) beats everything

If you go over 21 → you lose

If the computer goes over 21 → you win

Higher score wins if both are under 21

📌 Example Output
Your cards: [10, 11], current score: 21
Computer's first card: 7
Win with a Blackjack 😎

🚀 Future Improvements (Optional Ideas)

Add betting system 💰

Track wins/losses 📊

Multiplayer mode 👥

GUI version using Tkinter or Pygame 🖥️

👤 Author

Divyansh Rai
Python Learner | Aspiring Developer
