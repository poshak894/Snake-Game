# Snake-Game
# 🐍 Snake Game — JavaScript, HTML, CSS

A simple and modern Snake Game built using **Vanilla JavaScript**, **HTML**, and **CSS**.  
The game includes score tracking, a timer, high-score saving (via localStorage), and smooth grid-based movement.

---

## 🚀 Demo
👉 **Live Game:**  
https://poshak894.github.io/Snake-Game/

---

## 🎮 Features

- 🟩 Fully functional Snake gameplay  
- 🧊 Grid-based movement system  
- 🍎 Random food spawning  
- 🏆 High score saved automatically  
- ⏱️ Game timer  
- 🎨 Modern UI with modal screens  
- 🔄 Restart functionality  
- ⌨️ Keyboard controls (Arrow keys + WASD)  
- 📱 Responsive layout  

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| Arrow Up / W | Move Up |
| Arrow Down / S | Move Down |
| Arrow Right / D | Move Right |
| Arrow Left / A | Move Left |

---

## 🧱 How It Works

### 1. Board Generation
The board is generated dynamically using a grid layout.  
Each cell is stored using coordinates like:

```
blocks["row-col"]
```

### 2. Snake Movement
The snake moves by:
- Creating a new head  
- Unshifting it into the snake array  
- Removing the tail (unless food is eaten)

### 3. Food Mechanics
- Food spawns at random positions  
- Eating food increases score by **10**  
- Snake grows after eating  

### 4. Collision Detection
- Wall collision ends the game  
- Body collision can be added later

---

## 📁 Project Structure

```
/
|- index.html    # Main HTML structure
|- style.css     # Game styling
|- index.js      # Game logic
|- README.md     # Project documentation
```

---

## 📦 Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/snake-game.git
```

2. Open the folder:
```bash
cd snake-game
```

3. Open `index.html` in your browser.

No server required.

---

## 🌐 Deploy on GitHub Pages

1. Go to **Settings** in your repository  
2. Find **Pages**  
3. Set:
   - **Source:** Deploy from branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`  
4. Save

Your project will be live in a few seconds.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- LocalStorage API

---

## 🔮 Future Improvements

- Add body collision detection  
- Add game sounds  
- Add mobile touch controls  
- Add difficulty levels  
- Add animations  
- Add leaderboard  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve.

---

## 📜 License

This project is licensed under the **MIT License**.
