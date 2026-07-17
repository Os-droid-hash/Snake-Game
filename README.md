# 🐍 SlitherSpeller

SlitherSpeller is a console-based word game developed in **C** that combines the classic Snake game with word formation mechanics. Players control a snake to collect letters scattered across the board and form valid **three-letter English words**. The objective is to submit six correct words while avoiding three incorrect submissions and preventing collisions with walls or the snake itself.

---

## 📌 Features

- 🎮 Classic Snake gameplay
- 🔤 Letter collection and word formation
- ✅ Dictionary validation for 3-letter English words
- ⌨️ Press **Enter** to submit collected words
- 🏆 Win by submitting **6 correct words**
- ❌ Lose after **3 incorrect submissions**
- 🐍 Snake grows as letters are collected
- 💬 Fun feedback messages after every submission
- 🎲 Randomized letter placement for replayability

---

## 🛠️ Technologies Used

- C Programming
- Windows Console API
- Standard C Libraries
- `conio.h`
- `windows.h`

---

## 🎯 How to Play

1. Run the game.
2. Use the **Arrow Keys** to move the snake.
3. Collect **3 letters**.
4. Press **Enter** to submit the collected letters as a word.
5. If the word exists in the dictionary:
   - Score increases.
   - Correct word count increases.
6. If the word is incorrect:
   - You receive one strike.
7. Win after finding **6 correct words**.
8. Lose after **3 strikes** or if the snake crashes.

---

## 🎮 Controls

| Key | Action |
|------|--------|
| ↑ ↓ ← → | Move Snake |
| Enter | Submit Word |

---

## 📂 Project Structure

```
SlitherSpeller/
│── SlitherSpeller.c
│── README.md
```

---

## 🚀 Future Improvements

- Multiple rounds and difficulty levels
- Larger English dictionary
- Categories (Animals, Food, Places, etc.)
- High score system
- File handling for saving scores
- Colored console interface
- Sound effects
- Timer and bonus points

---

## 👨‍💻 Author

**Osailah**

BS Computer Science Student

---

## 📜 License

This project is created for educational purposes and personal learning.
