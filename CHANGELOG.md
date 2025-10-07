# Changelog

All notable changes to the Multiplication Tables Game will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2025-10-06

### 🎯 Mobile UX Optimization

This release focuses on dramatically improving the mobile user experience with streamlined gameplay and better touch interaction.

#### ✨ Enhanced Features

- **Visible ENTER Button on Mobile**: Added prominent ENTER button for easy answer submission on touch devices
- **Auto-Submit on 3 Digits**: Automatic submission when 3-digit answers are entered, reducing need for manual submission
- **Persistent iOS Keyboard**: Enhanced keyboard management with multiple refocus attempts to prevent iOS keyboard from hiding
- **Improved Touch Handling**: Better button touch response and keyboard persistence during gameplay
- **Compact Mobile Stats**: Streamlined statistics display optimized for smaller screens
- **Reduced Visual Clutter**: Hidden decorative stars on mobile devices to focus attention on gameplay
- **Optimized Layout**: Better element sizing and positioning for mobile touch targets

#### 🎨 Mobile Design Improvements

- **Responsive Button Sizing**: ENTER button scales appropriately for mobile screens
- **Touch-Friendly Controls**: Larger touch targets and better spacing for fingers
- **Clean Mobile Interface**: Removed distracting elements during mobile gameplay
- **Improved Keyboard Flow**: Seamless keyboard interaction without unexpected hiding

#### 🛠️ Technical Enhancements

- **Multiple Focus Attempts**: Robust keyboard focus system for various mobile browsers
- **Enhanced Event Handling**: Improved button press detection and response
- **Mobile-Specific CSS**: Targeted styles for mobile devices and small screens
- **Performance Optimization**: Faster response times on mobile devices

#### 📱 Mobile-First Improvements

- **Immediate Game Start**: Faster entry into gameplay on mobile devices
- **Streamlined UI Flow**: Reduced steps between game start and active play
- **Better Mobile Navigation**: Improved touch navigation throughout the app

## [1.0.0] - 2025-10-05

### 🎉 Initial Release

#### ✨ Features

- **Interactive Multiplication Table Game (1-12)**: Complete 12x12 multiplication table with dynamic challenges
- **Smart Error Tracking**: Adaptive algorithm that focuses on cells where the user makes more mistakes
- **Repetition System**: Special sequence of 15 challenges activated when errors occur or response time > 6 seconds
- **Real-time Statistics Dashboard**:
  - ⏱️ Total elapsed time with live countdown
  - ⚡ Last challenge response time
  - 📊 Average response time (last 10 challenges)
  - ✅ Accuracy percentage (last 10 challenges)
  - 🎯 Dynamic score calculation: `(accuracy / average_time) × 100`
  - 🏆 High score tracking with spectacular animation
- **Performance Metrics**: Tracks response times and accuracy for continuous improvement
- **Player Profiles**: Enter your name to personalize the experience
- **Screenshot Functionality**: Capture and save your scores to share achievements
- **Feedback System**: Direct link to Google Forms for user suggestions

#### 🎨 Design

- **Modern Gradient UI**: Vibrant purple-pink animated gradients throughout
- **Kid-Friendly Interface**:
  - Fredoka One font for titles (playful and rounded)
  - Quicksand font for body text (clean and readable)
  - Emojis integrated throughout the interface
  - Colorful gradient buttons with hover effects
- **Responsive Two-Column Layout**:
  - Left panel: Controls and statistics (sticky positioning)
  - Right panel: Game table (always fully visible)
- **Fully Adaptive Design**:
  - Uses CSS `clamp()` for fluid typography
  - Viewport units (vw/vh) for proportional sizing
  - Perfect display from mobile (320px) to 4K screens
  - No horizontal scrolling on any device
- **Smooth Animations**:
  - Floating table effect
  - Bouncing title animation
  - Twinkling star decorations
  - Pulse animation on Start button
  - Pop animation for correct answers
  - Shake animation for incorrect answers
  - Spectacular high score celebration with rotation and glow
- **Visual Feedback**:
  - 🟢 Green gradient for correct answers with bounce effect
  - 🔴 Red gradient for incorrect answers with shake effect
  - 🟡 Yellow gradient for highlighted cells
  - Modal overlay showing correct answer when wrong

#### 🎮 Game Mechanics

- **Weighted Random Selection**: Cells with more errors have higher probability of being selected
- **Progressive Difficulty**: Adaptive learning system that targets weak areas
- **Visual Highlighting**: Cross-pattern highlighting of current row and column
- **Instant Feedback**: Immediate visual and textual confirmation of answers
- **Error Recovery**: Special 15-challenge sequence to reinforce learning after mistakes

#### 📱 Responsive Breakpoints

- **Desktop (> 1400px)**: Optimal two-column layout with large elements
- **Laptop (1024px - 1400px)**: Balanced two-column layout
- **Tablet (700px - 1024px)**: Vertical layout with statistics in 2 columns
- **Mobile (< 700px)**: Single column, compact layout with optimized touch targets

#### 🛠️ Technical Features

- **Pure HTML/CSS/JavaScript**: No dependencies, works offline
- **LocalStorage**: High score persistence across sessions
- **HTML2Canvas Integration**: Screenshot functionality via CDN
- **Cross-browser Compatible**: Works on all modern browsers
- **Accessible**: Keyboard navigation support (Enter key to submit)

#### 📦 Files Included

- `index.html` - Main application file (single-file architecture)
- `README.txt` - Basic project information

#### 🎯 Target Audience

- **Age Range**: 6-12 years old
- **Purpose**: Fast and fun multiplication training for kids
- **Educational Value**: Gamified learning with score incentives

#### 🌐 Deployment

- **Platform**: Web browser (no installation required)
- **Hosting**: Compatible with GitHub Pages, Netlify, Vercel, or any static hosting
- **URL Format**: Simply open `index.html` in any modern browser

---

### Future Roadmap (Coming Soon)

- [ ] Multi-language support (Spanish, English, French, Portuguese)
- [ ] Sound effects and background music toggle
- [ ] Difficulty levels (easy, medium, hard)
- [ ] Leaderboard system
- [ ] Progress tracking over time
- [ ] Print certificates of achievement
- [ ] Parent/teacher dashboard
- [ ] Customizable table ranges (e.g., 1-10, 1-15)
- [ ] Dark mode toggle

---

**Note**: This is the first official release! We appreciate your feedback to make this tool even better for kids learning multiplication tables.
