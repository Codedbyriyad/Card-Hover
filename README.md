# 🎴 Pokémon Cards — Hover Effect

A visually stunning **Pokémon Cards** showcase built with pure HTML and CSS, featuring smooth hover animations that bring each card to life.

🔗 **Live Demo:** [hover-games.netlify.app](https://hover-games.netlify.app)

---

## ✨ Features

- 🃏 Interactive Pokémon card grid layout
- 🎞️ Smooth CSS hover animations and transitions
- 🖼️ High-quality Pokémon imagery via Unsplash
- 📱 Clean, minimal design
- ⚡ No JavaScript — pure HTML & CSS magic

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & markup |
| CSS3 | Styling, hover effects & transitions |
| Unsplash API | Pokémon card images |
| Netlify | Deployment & hosting |

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser
- A code editor (VS Code recommended)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Codedbyriyad/hover-games.git
   ```

2. **Navigate into the project folder:**
   ```bash
   cd hover-games
   ```

3. **Open in browser:**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```
   Or drag and drop `index.html` into your browser.

---

## 📁 Project Structure

```
hover-games/
│
├── index.html       # Main HTML file with card layout
├── style.css        # CSS hover effects & animations
└── README.md        # Project documentation
```

---

## 🎮 How It Works

Each Pokémon card is built using a simple `div` element styled with CSS. On hover, CSS `transform`, `transition`, and `box-shadow` properties create a 3D lift and glow effect, making the cards feel interactive and alive.

```css
.card:hover {
  transform: scale(1.1) translateY(-10px);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
  transition: all 0.3s ease;
}
```

---

## 🌐 Deployment

This project is deployed on **Netlify** with continuous deployment from GitHub.

To deploy your own version:
1. Push your code to a GitHub repository
2. Connect the repo to [Netlify](https://netlify.com)
3. Deploy in one click — done! ✅

---

## 🙌 Contributing

Contributions are welcome! Feel free to:
- Add more Pokémon cards
- Improve hover animations
- Make it responsive for mobile devices

```bash
# Fork the repo, make changes, then open a Pull Request
git checkout -b feature/your-feature-name
git commit -m "Add: your feature description"
git push origin feature/your-feature-name
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Made with ❤️ and CSS by **[Kaysar Mahmud](https://github.com/Codedbyriyad)**

> *"Gotta hover 'em all!"* 🔥

---

⭐ If you like this project, don't forget to **star the repository!**
