# 🎮 Rock-Paper-Scissors Game Demo

A fun and interactive Rock-Paper-Scissors game built with **Streamlit**. Play against the computer and see if you can win!

## 📋 Features

- 🎯 Simple and intuitive UI
- 🤖 Play against a random computer choice
- 🖼️ Visual display of both player and computer choices
- 🏆 Real-time win/loss/tie determination
- 📱 Responsive web-based interface

## 🛠️ Tech Stack

- **Python** - Core programming language
- **Streamlit** - Web framework for building interactive applications

## 📦 Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/armancodes0/RPS-DEMO.git
   cd RPS-DEMO
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

To run the application:

```bash
streamlit run app.py
```

The app will open in your default web browser at `http://localhost:8501`

### How to Play

1. Select your choice: **Rock**, **Paper**, or **Scissor**
2. Click the **PLAY** button
3. The computer will make a random choice
4. See the result:
   - 🏆 **You win!** - Your choice beats the computer's choice
   - 🤝 **It's a tie!** - Both chose the same option
   - 😢 **You lose!** - Computer's choice beats yours

## 📁 Project Structure

```
RPS-DEMO/
├── app.py                          # Main Streamlit application
├── requirements.txt                # Python dependencies
├── rock.jpeg                       # Rock image asset
├── paper.jpeg                      # Paper image asset
├── scissor.jpeg                    # Scissor image asset
└── README.md                       # This file
```

## 🎮 Game Rules

- **Rock** beats **Scissor**
- **Paper** beats **Rock**
- **Scissor** beats **Paper**
- Same choices result in a **tie**

## 📝 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## 💡 Future Enhancements

- Add score tracking across multiple games
- Difficulty levels (easy, medium, hard)
- Multiplayer support
- Sound effects and animations
- Game statistics and history

---

**Made by [armancodes0](https://github.com/armancodes0)**
