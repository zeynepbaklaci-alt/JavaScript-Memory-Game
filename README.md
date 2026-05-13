# 🧠 Memory Card Game

A simple and interactive **Memory Matching Game** built using **HTML, CSS, and JavaScript**. The goal is to find matching pairs of cards by flipping them over.

---

## 🚀 Features

- Dynamic card generation using JavaScript  
- Card flipping animation  
- Matching logic  
- Responsive grid layout  
- Duplicate card system for pairs  

---

## 🛠️ Technologies Used

- HTML5  
- CSS3 (Flexbox & animations)  
- Vanilla JavaScript (DOM manipulation)

---

## 📸 How It Works

### 1. Duplicate cards to create pairs
```js
var gameGrid = cardsArray.concat(cardsArray);
```

### 2. Create cards dynamically
```js
var card = document.createElement('div');
```

### 3. Each card is assigned:
- A class (`card`)
- A data attribute (`data-name`)
- A background image

### 4. Display
Cards are placed in a grid and flip when clicked.


📁 Project Structure
project-folder/
│
├── index.html
├── style.css
├── main.js
└── README.md

⚙️ Setup & Usage

1. Clone or download the project
2. Open index.html in your browser
3. Start playing 🎮

🧩 Game Logic (Basic)

1. Click a card to reveal it
2. Click another card to find a match
3. If both cards match → they stay flipped
4. If not → they flip back

Author

ZEYNEP BAKLACI

Product Software Engineer – Barcelona
  