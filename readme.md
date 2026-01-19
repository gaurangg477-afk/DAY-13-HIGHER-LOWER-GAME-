# 🔼 Higher or Lower Game (Python)

A fun command-line game built using Python where the player guesses which of two famous personalities or brands has more followers on social media.

This project is inspired by **Day 14** of **Dr. Angela Yu’s “100 Days of Code: Python”** course.

---

## 🎮 How the Game Works

- Two accounts are randomly selected.
- The player is shown basic information about both.
- The player guesses which account has **more followers**.
- If the guess is correct:
  - The score increases by 1
  - The game continues
- If the guess is wrong:
  - The game ends
  - Final score is displayed

---

## 🧠 Concepts Used

- Python dictionaries and lists  
- Random module  
- Functions with return values  
- While loops  
- Conditional logic  
- User input handling  
- Game state management  

---

## 📂 Project Structure

Higher-Lower-Game/
│
├── main.py # Main game logic
├── game_data.py # Data for accounts and follower counts
├── art.py # ASCII art for logo and VS symbol
└── README.md # Project documentation

yaml
Copy code

---

## ▶️ How to Run the Game

1. Make sure Python is installed on your system
2. Clone this repository or download the files
3. Open a terminal in the project folder
4. Run the game using:

```bash
python main.py
🖥️ Sample Gameplay
vbnet
Copy code
Compare A: Instagram, a Social media platform, from United States
VS
Against B: Cristiano Ronaldo, a Footballer, from Portugal

Who has more followers? Type 'A' or 'B': A

You're right! Current score: 1
🚀 Future Improvements
Add more data entries

Add difficulty levels

Add a replay option

Add a graphical user interface (GUI)