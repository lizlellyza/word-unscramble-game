# 🎮 Word Unscramble Game - Multiplayer Edition

An interactive multiplayer word unscramble game where colleagues can compete together to solve scrambled words!

## 🚀 Live Demo
**[Play the Game](https://github.com/yourusername/word-unscramble-game)** - Replace with your GitHub Pages URL

## ✨ Features

### 🎯 Game Modes
- **Level 1 (Easy)**: 5 simple words
- **Level 2 (Moderate)**: 5 medium difficulty words
- **Level 3 (Difficult)**: 5 challenging words

### 👥 Multiplayer Features
- **Player Registration**: Each player enters their name before playing
- **Live Leaderboard**: Real-time score tracking with 👥 Players button
- **First to Answer Tracking**: See who answered each word correctly first
- **Final Rankings**: 🥇🥈🥉 Medal rankings after each level
- **Persistent Scores**: Player scores saved in browser storage

### 📊 Game Features
- Instant feedback (correct/incorrect answers)
- Helpful hints for each word
- Skip option to move to next word
- Individual score tracking
- Progress bar showing current word number
- Email results to any address

### 📱 Design
- Beautiful gradient UI
- Fully responsive (desktop, tablet, mobile)
- Smooth animations and transitions
- User-friendly interface

## 🎮 How to Play

1. **Open the game** in your browser
2. **Enter your name** when prompted
3. **Select a difficulty level** (1, 2, or 3)
4. **Unscramble the word** and type your answer
5. **Submit** or press **Enter**
6. **View the leaderboard** by clicking 👥 Players
7. **Complete all 5 words** to see final results
8. **Email your results** to share with others

## 🏆 Features Explained

### Live Leaderboard
- Click **👥 Players** button during gameplay
- See all players and their current scores
- Updates in real-time as players answer correctly

### First to Answer
- The game tracks who answered each word **first**
- When someone gets the first correct answer, a special celebration message appears
- Subsequent correct answers are also tracked
- All answers visible during gameplay

### Final Rankings
- After completing a level, see the final leaderboard
- Players ranked by total score
- Medal indicators (🥇🥈🥉)
- Your individual results displayed

### Email Results
- Send game results to any email
- Includes your score, all answers, and final leaderboard
- Pre-filled with your email (configurable)

## 📋 Word Lists

### Level 1 (Easy)
- CAT, DOG, ERE, ART, SUN

### Level 2 (Moderate)
- PART, ROSE, RATE, STOP, TEAMS

### Level 3 (Difficult)
- STABLE, SILENT, CARTOON, TREASON, ARTICLES

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies needed
- **Browser Storage** - Player data stored in localStorage
- **Responsive Design** - Works on all devices
- **Email Service** - Uses Formspree for email functionality
- **HTTPS Ready** - Secure by default on GitHub Pages

## 📦 File Structure

```
word-unscramble-game/
├── index.html          # Main game file (complete HTML+CSS+JS)
├── README.md           # This file
└── DEPLOY_INSTRUCTIONS.md  # Deployment guide
```

## 🚀 Deployment

### GitHub Pages (Free & Easy)
1. Create a GitHub repository
2. Upload `index.html`
3. Enable GitHub Pages in Settings
4. Access via `https://yourusername.github.io/word-unscramble-game`

### Netlify (Alternative)
1. Sign up at netlify.com
2. Connect your GitHub repository
3. Automatic deployment with HTTPS
4. Get a custom domain option

## 📝 How to Customize

### Change Word Lists
Edit the `gameData` object in the JavaScript section:
```javascript
const gameData = {
    1: {
        name: 'Easy',
        words: [
            { scrambled: 'TAC', answer: 'CAT', hint: 'A furry pet' },
            // Add more words...
        ]
    },
    // Level 2 and 3...
};
```

### Change Email Recipient
Edit the pre-filled email in the form:
```html
<input value="your-email@example.com">
```

### Customize Colors
Edit the CSS gradient colors:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 💾 Data Storage

- **Browser Local Storage**: Player names and scores stored locally
- **No Server Required**: Game runs entirely in the browser
- **Privacy**: All data stays on the user's device
- **Persistence**: Data remains until browser cache is cleared

## 🐛 Troubleshooting

### Email not sending?
- Check your internet connection
- Try a valid email address
- Check browser console for errors

### Scores not saving?
- Clear browser cache and try again
- Check if local storage is enabled
- Different browsers/devices = different storage

### Game not loading?
- Check if you're on HTTPS
- Try a different browser
- Clear browser cache
- Check internet connection

## 🎓 Educational Use

Perfect for:
- Team building activities
- Classroom games
- Corporate events
- Language learning
- Brain teasers and puzzles

## 📞 Support

For issues or suggestions:
1. Check the troubleshooting section
2. Review the code comments
3. Check browser console for errors (F12)

## 📄 License

This project is free to use and modify for personal and commercial purposes.

---

**Enjoy the game! 🎮** 

**Made with ❤️ for word lovers and game enthusiasts**
