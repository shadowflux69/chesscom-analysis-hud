# Chess.com Analysis HUD

A Chrome extension that adds a mini HUD overlay on chess.com analysis pages.  
It detects the current board state, displays it as a mini-board, shows the FEN string, and can connect to a local Stockfish WASM engine for move suggestions in **analysis/review only** (never in live games).

---

## ✨ Features
- Mini-board HUD that updates automatically with the current position  
- FEN export for use in other tools  
- Optional integration with Stockfish WASM for local best-move suggestions  
- Configurable engine path via extension options  

---

## 🚧 Known Issues
- The Stockfish engine may not start if the JS/WASM files are missing or misconfigured  
- Some black pieces may occasionally appear as white  
- The board can sometimes be flipped compared to the chess.com orientation  
- I am new to coding and still learning, so I don’t yet know how to fix these issues

---

## 🤝 Contributing
I’d love help improving this project!  
If you know Chrome extensions, JavaScript, or working with Stockfish WASM, your contributions would be very welcome.  

Ways you can help:
- Fix board orientation / piece color bugs  
- Improve the HUD design and scaling  
- Simplify engine integration and error handling  
- Write documentation or tutorials for other new coders  

Please feel free to **fork this repo**, make improvements, and open a pull request. Even small fixes are appreciated!

---

## 📦 Installation
1. Clone or download this repository  
2. Go to `chrome://extensions` in Chrome  
3. Enable **Developer mode** (top right)  
4. Click **Load unpacked** and select the project folder  
5. Open chess.com’s **Analysis** page and the HUD should appear  

---

## ⚖️ Fair Play Note
This extension is designed for **analysis only**.  
It does **not** run on live chess.com games and should never be used for in-game assistance.  

---
