# 🎮 Multiplication Tables Game (1 to 12) ⭐

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Web-orange.svg)

> A fun, interactive, and educational game designed to help children master multiplication tables from 1 to 12.

---

## 📖 Overview

This is a **web-based multiplication game** created to help kids (ages 6-12) learn their multiplication tables through gamification. The app features an adaptive learning system that focuses on areas where the student needs more practice, making learning both efficient and enjoyable!

### ✨ Key Features

- 🎯 **Smart Adaptive Learning** - Automatically focuses on multiplication facts where errors occur
- 📊 **Real-time Performance Tracking** - Monitor speed, accuracy, and overall score
- 🏆 **High Score System** - Motivate learning with achievement tracking
- 🎨 **Beautiful Kid-Friendly Design** - Colorful gradients, animations, and emojis
- 📱 **Fully Responsive** - Perfect display on desktop, tablet, and mobile
- 📸 **Screenshot Feature** - Save and share achievements
- 🌐 **Works Offline** - No internet required after loading
- ⚡ **Zero Installation** - Just open in a browser and play!

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

1. **Enter Your Name** - Personalize your experience
2. **Click Start** - The game will randomly select a multiplication problem
3. **Type Your Answer** - Enter the result in the highlighted cell
4. **Press Enter** - Submit your answer
5. **Get Feedback** - See if you're correct with visual and textual feedback
6. **Track Progress** - Monitor your statistics in the left panel
7. **Beat Your High Score** - Try to improve your score with each session!

### 🎯 Scoring System

Your score is calculated as:
```
Score = (Accuracy Percentage / Average Time) × 100
```

- **Higher accuracy** = Higher score
- **Faster responses** = Higher score
- **Consistency matters** - Score is based on your last 10 attempts

---

## 📊 Statistics Tracked

| Metric | Description |
|--------|-------------|
| ⏱️ **Total Time** | Cumulative time since starting the session |
| ⚡ **Last Challenge** | Time taken to answer the most recent question |
| 📊 **Average** | Average response time for the last 10 challenges |
| ✅ **Last 10 Accuracy** | Percentage of correct answers in last 10 attempts |
| 🎯 **Score** | Current performance score |
| 🏆 **Higher Score** | Best score achieved (appears after 10+ challenges) |

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
```
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

### What this means:
- ✅ Free to use
- ✅ Free to modify
- ✅ Free to distribute
- ✅ Can be used commercially
- ⚠️ No warranty provided

---

## 👨‍👩‍👧‍👦 About

**Created by**: Rodrigo Figueroa  
**Location**: Chile 🇨🱼  
**Contact**: rfiguerc@uc.cl  
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

**Current Version**: 1.0.0 (Initial Release)  
**Release Date**: October 5, 2025

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

---

<div align="center">

**Made with ❤️ for kids learning multiplication**

[Report Bug](https://github.com/frenetico55555/times_tables_challenge/issues) · [Request Feature](https://forms.gle/AvHgLfGM7LdmSfbt6) · [View Demo](https://frenetico55555.github.io/times_tables_challenge)

</div>
