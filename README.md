# Blackjack Game 🃏

A classic Blackjack card game built with vanilla JavaScript, HTML, and CSS.

## 🎮 How to Play

1. Click **START GAME** to begin with two random cards
2. Your goal is to get as close to 21 as possible without going over
3. Click **NEW CARD** to draw additional cards
4. Face cards (J, Q, K) count as 10, Aces count as 11
5. If you get exactly 21, you win with Blackjack!
6. If you go over 21, you're out of the game

## 🚀 Live Demo

[Play the game here](https://GeekKwame.github.io/blackjack-game)

## 🛠️ Features

- **Random Card Generation**: Each card is randomly generated (1-13)
- **Smart Card Values**: Face cards = 10, Aces = 11
- **Game State Management**: Tracks wins, losses, and game status
- **Responsive Design**: Works on desktop and mobile devices
- **Smooth Animations**: Hover effects and transitions

## 📁 Project Structure

```
blackjack-game/
├── index.html          # Main HTML file
├── index.js           # Game logic and functionality
├── styles.css         # Styling and animations
├── images/
│   └── table.png      # Background image
└── README.md          # This file
```

## 🎯 Game Rules

- **Blackjack**: Exactly 21 points with first two cards
- **Bust**: Over 21 points - you lose
- **Hit**: Draw another card
- **Stand**: Keep current cards

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/GeekKwame/blackjack-game.git
   ```

2. Open `index.html` in your web browser

3. Start playing!

## 🎨 Customization

- **Player Name**: Change `player.name` in `index.js`
- **Starting Chips**: Modify `player.chips` value
- **Styling**: Edit `styles.css` for different themes
- **Card Values**: Adjust `getRandomCard()` function

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by Edmund
