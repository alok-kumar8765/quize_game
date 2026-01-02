# 🎮 Hybrid Age-Based Quiz Game (Python)

A **fun, offline, age-based quiz game** written in Python that asks **random questions** based on the user’s age group and displays the final score.

This project is designed to:

* Attract **kids & beginners** to coding
* Demonstrate **clean Python architecture**
* Work **100% offline** (no API / no internet required)

---

## ✨ Features

✅ Age-based quiz system
✅ Multiple age groups (kids → adults)
✅ Randomized questions every run
✅ Score tracking (correct / wrong)
✅ Simple, readable, beginner-friendly code
✅ Uses modern Python libraries (`pydantic`, `polars`)

---

## 🧠 Age Groups Supported

| Age Group       | Description                     |
| --------------- | ------------------------------- |
| **1–5 years**   | Colors, animals, basic counting |
| **6–10 years**  | Simple math & general knowledge |
| **11–15 years** | Science, math, logic            |
| **16–30 years** | Programming & general awareness |

---

## 🛠 Tech Stack

* **Python 3.9+**
* **Pydantic** → structured question models
* **Polars** → fast & clean score handling
* **Random** → question shuffling

---

## 📂 Project Structure

```
hybrid-quiz/
│
├── quiz.py          # Main quiz program
├── README.md        # Project documentation
```

---

## 📦 Installation

### 1️⃣ Clone the repository (or copy the file)

```bash
git clone https://github.com/alok-kumar8765/quize_game.git
cd quize_game
```

### 2️⃣ Install dependencies

```bash
pip install polars pydantic
```

---

## ▶️ How to Run

```bash
python quiz.py
```

---

## 🎯 How It Works

1. User selects an **age group**
2. Program randomly selects **up to 10 questions**
3. User answers questions one by one
4. Score is tracked using **Polars DataFrame**
5. Final result is displayed with encouragement 🎉

---

## 🧪 Example Output

```
Choose Age Group:
1️⃣ 1-5 years
2️⃣ 6-10 years
3️⃣ 11-15 years
4️⃣ 16-30 years

Enter choice: 2

🎮 QUIZ STARTED 🎮

🤖 What is 5 + 5?
🧒 Your answer: 10
🎉 Correct!

🏆 QUIZ OVER 🏆
✅ Correct: 4
❌ Wrong: 1
🌟 Excellent work!
```

---

## 🚀 Future Enhancements (Ideas)

* 🔊 Voice-based quiz (Text-to-Speech)
* 🧠 AI-generated questions (Ollama / Gemini)
* 🌍 Multi-language support
* 🎨 GUI or Web version
* 🏆 Levels, badges & leaderboard
* 👨‍👩‍👧 Parent progress dashboard

---

## 🤝 Contribution

Contributions are welcome!
You can:

* Add more questions
* Add new age groups
* Improve UI/UX
* Convert to web/mobile app

---

## 📜 License

This project is **open-source** and free to use for learning and educational purposes.

---

## ❤️ Made for Learning

> “The best way to learn coding is by playing.”

Happy Coding 🚀
