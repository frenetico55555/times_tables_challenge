# 🎮 Multiplication Tables Game (1 to 12) ⭐

![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Web-orange.svg)

> A fun, interactive, and educational game designed to help children master multiplication tables from 1 to 12.

---

## 📖 Overview

This is a **web-based multiplication game** created to help kids (ages 6-12) learn their multiplication tables through gamification. The app features an adaptive learning system that focuses on areas where the student needs more practice, making learning both efficient and enjoyable!

### ✨ Key Features


---

## 🆕 New in v1.1: Multi-user, Secure Progress & Visual History

- 👤 **User Registration & Login** – Each child can create a personal account with a simple password
- 🔐 **Password Protection** – Only the correct password allows access to a user's progress
- 📈 **Score History Panel** – See your last 10 scores and session dates
- ✨ **Sparkline Visualization** – Mini graph showing recent score evolution (desktop & mobile)
- 🏅 **Personal Best Tracking** – Shows personal best vs current session performance
- 🧑‍🎓 **Kid & Parent Friendly** – Clear messages, accessible interface and feedback
- 🌍 **Fully Responsive & Accessible** – Works across desktop, tablet and mobile

---

---

## 🚀 Quick Start

### Option 1: Direct Use

1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Enter your name and click "🚀 Start Game!"
4. Start solving multiplication problems!

### Option 2: Try it Online

Visit: **[https://frenetico55555.github.io/times_tables_challenge](https://frenetico55555.github.io/times_tables_challenge)**

---

## 🎮 How to Play

1. **Create or Select Your Player** - Register a new player with a simple password, or select an existing one
2. **Start the Game** - The app will choose multiplication challenges for you
3. **Answer & Submit** - Type your answer and press Enter (or tap the button on mobile)
4. **See Your Progress** - Visual feedback, stats, and your score history update instantly
5. **Track Your Improvement** - View your personal best and sparkline graph in the stats panel

### 🎯 Scoring System

Your score is calculated as:

```text
Score = (Accuracy Percentage / Average Time) × 100
```

- **Higher accuracy** = Higher score
- **Faster responses** = Higher score
- **Consistency matters** - Score is based on your last 10 attempts

---

## 📊 Statistics Tracked

| Métrica | Descripción |
|---------|-------------|
| ⏱️ **Tiempo total** | Tiempo acumulado desde el inicio de la sesión |
| ⚡ **Último reto** | Tiempo para responder el último desafío |
| 📊 **Promedio** | Tiempo promedio de respuesta (últimos 10 retos) |
| ✅ **Últimos 10 aciertos** | Porcentaje de respuestas correctas en los últimos 10 intentos |
| 🎯 **Score** | Puntuación actual |
| 🏆 **Mejor Score** | Mejor puntuación lograda (aparece tras 10+ retos) |
| 📈 **Historial visual** | Lista y gráfico de los últimos 10 scores |

---

## 🧠 Adaptive Learning Algorithm

The game uses an intelligent system to help you learn efficiently:

1. **Error Tracking** - Each cell tracks how many times you've gotten it wrong
2. **Weighted Selection** - Cells with more errors are chosen more frequently
3. **Reinforcement Sequence** - When you make a mistake OR take > 6 seconds:
   - You'll get a special 15-challenge sequence
   - The problematic cell appears 5 times
   - Interspersed with 10 easier problems (from 1-4 tables)
   - This spacing helps reinforce memory retention

---

## 🎨 Design Features

### Visual Elements

- **Animated Gradient Background** - Purple-pink shifting colors
- **Floating Table** - Subtle up-and-down animation
- **Twinkling Stars** - Decorative elements throughout ⭐✨🌟💫
- **Colorful Buttons** - Each with unique gradient and hover effects
- **Smooth Transitions** - All interactions have polished animations

### Responsive Design

- **Desktop (1400px+)**: Two-column layout with optimal spacing
- **Laptop (1024-1400px)**: Balanced two-column layout
- **Tablet (700-1024px)**: Vertical layout, stats in 2 columns
- **Mobile (<700px)**: Single column, touch-optimized

---

## 🛠️ Technical Details

### Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling, animations, and responsive design
  - CSS Grid & Flexbox for layout
  - CSS Variables for theming
  - `clamp()` for fluid typography
  - Viewport units for responsive sizing
- **Vanilla JavaScript** - All game logic and interactivity
- **HTML2Canvas** - Screenshot functionality (loaded via CDN)

### Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

**Minimum Requirements**: Any modern browser with ES6 support

### File Structure

```text
times_tables_challenge/
├── index.html          # Main application (all-in-one file)
├── README.md           # This file
├── README.txt          # Simple text version
├── CHANGELOG.md        # Version history
└── LICENSE             # MIT License
```

---

## 📸 Screenshots

### Desktop View

The game features a clean two-column layout with controls on the left and the multiplication table on the right.

### Mobile View

Fully responsive design adapts to smaller screens with a vertical layout.

---

## 🎓 Educational Use

This game is perfect for:

- **Parents** - Help your children practice multiplication at home
- **Teachers** - Use in classroom settings or assign for homework
- **Students** - Self-directed learning and practice
- **Tutors** - Supplementary tool for math tutoring sessions

### Recommended Usage

- **Daily Practice**: 10-15 minutes per day
- **Goal Setting**: Challenge kids to beat their high score
- **Rewards System**: Use screenshots as proof of achievement for rewards
- **Progress Tracking**: Monitor improvement over time

---

## 🤝 Contributing

We welcome feedback and suggestions!

### How to Contribute

1. Try the game and identify areas for improvement
2. Click the "💡 Send Suggestions" button in the app
3. Fill out the Google Form with your feedback
4. Or open an issue on GitHub

### Planned Features

See [CHANGELOG.md](CHANGELOG.md) for our roadmap of upcoming features.

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means

- ✅ Free to use
- ✅ Free to modify
- ✅ Free to distribute
- ✅ Can be used commercially
- ⚠️ No warranty provided

---

## 👨‍👩‍👧‍👦 About

**Created by**: Rodrigo Figueroa  
**Location**: Chile 🇨🱼  
**Contact**: <rfiguerc@uc.cl>  
**GitHub**: [@frenetico55555](https://github.com/frenetico55555)

### The Story

This game was created for my children to help them learn multiplication tables. They loved it so much that they started competing for prizes based on their high scores. Within just one week, they had memorized all the tables!

When they shared it with their friends, other parents asked for access to the game. That's why we decided to publish it here - to help more children learn multiplication in a fun and engaging way! 🎉

---

## 🙏 Acknowledgments

- **Fonts**: [Google Fonts](https://fonts.google.com/) (Fredoka One, Quicksand)
- **Screenshot Library**: [HTML2Canvas](https://html2canvas.hertzen.com/)
- **Inspiration**: Our kids and their friends who tested and loved the game!

---

## 📞 Support

If you find this helpful, please:

- ⭐ Star this repository
- 🐛 Report bugs via GitHub Issues
- 💡 Share suggestions via the in-app form
- 📢 Share with other parents and teachers!

---

## 🌟 Version

**Current Version**: 1.1.0 (Multi-user & Cloud Sync)  
**Release Date**: October 8, 2025

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

---

### Made with ❤️ for kids learning multiplication

[Report Bug](https://github.com/frenetico55555/times_tables_challenge/issues) · [Request Feature](https://forms.gle/AvHgLfGM7LdmSfbt6) · [View Demo](https://frenetico55555.github.io/times_tables_challenge)
