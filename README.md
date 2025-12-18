# Legends of the Vault – Vault of Causes

A premium single-page slot-style game concept demo showcasing a unique cause-based gaming experience.

## 🎮 Game Overview

**Legends of the Vault** is an interactive MVP that demonstrates a slot game concept where every spin contributes to a social cause. Players select a cause, spin the reels, and build progress toward unlocking vaults that amplify their chosen cause's impact.

## ✨ Features

- **5-Column Slot Machine**: Spin with 5 reels for more exciting gameplay
- **Win Condition**: Win when you get at least 3 matching symbols
- **Cause Selection**: Choose from 3 different causes before playing
- **Impact Progression**: Progress bar that fills even on losses (reduced frustration)
- **Vault Unlocking**: Unlock vaults at 100 Impact Points
- **Session Stats**: Track spins, wins, vaults unlocked, and total impact
- **Fresh Start**: Game resets on every page refresh
- **Premium UI**: Dark vault-themed design with smooth animations
- **Mobile Responsive**: Works seamlessly on all device sizes

## 🎯 How to Play

1. **Select a Cause**: Choose one of three causes:
   - 🌱 Reforest City A
   - 🍽️ Food Support Initiative B
   - 🌊 Ocean Cleanup Program C

2. **Spin**: Click the SPIN button to play

3. **Win/Lose**:
   - **Win**: Get at least 3 matching symbols → +20 Impact Points
   - **Loss**: No match → +5 Impact Points (reduced frustration!)

4. **Progress**: Watch your Vault Progress bar fill up

5. **Unlock Vaults**: When you reach 100 Impact Points, a vault unlocks with amplification options

6. **Amplify**: Choose to amplify your cause (+5%, +10%) or skip after unlocking

## 🎲 Game Logic

- **Win Condition**: At least 3 matching symbols across the 5 reels
- **Impact Points**: 
  - Win: +20 points
  - Loss: +5 points
- **Vault Unlock**: At 100 Impact Points
- **Progress Reset**: After vault unlock, progress resets to 0
- **Fresh Start**: Game state resets on every page refresh

## 🛠 Technical Details

- **Single HTML File**: Everything in one file, no dependencies
- **Vanilla JavaScript**: No frameworks required
- **No Backend**: Fully client-side
- **localStorage**: Used for session state (cleared on refresh)

## 🚀 Running the MVP

Simply open `index.html` in any modern web browser. No server or build process required!

### For Development

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Then open http://localhost:8000 in your browser
```

## 📦 Project Structure

```
vault-game/
├── index.html          # Main game file (all-in-one)
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## 🌐 GitHub Pages Deployment

This project is ready for GitHub Pages deployment:

1. Push the repository to GitHub
2. Go to Settings → Pages
3. Select the branch (usually `main` or `master`)
4. Select the root directory
5. Click Save

The game will be available at: `https://[your-username].github.io/vault-game/`

## 🎨 Design Philosophy

- **Premium Feel**: Dark vault/stone/gold color scheme
- **Smooth Animations**: Reel spins, progress bar fills, modal transitions
- **Minimalist UI**: Clean, uncluttered interface
- **Mobile-First**: Responsive design for all screen sizes

## 📝 Notes

- This is a **demo MVP** for interviews and internal validation
- **No real money** is involved
- All game logic runs client-side
- Game state resets on every page refresh

## 🐛 Browser Support

Works in all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This is a concept demo. All rights reserved.

---

**Built with ❤️ for showcasing innovative gaming concepts**
