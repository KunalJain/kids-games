# 🎮 Kids Game Collection

A collection of fun browser games built with plain HTML, CSS, and JavaScript. No frameworks, no build steps — just open and play!

**Live site:** https://kunaljain.github.io/kids-games

---

## Games

| Game | Description | Skills |
|------|-------------|--------|
| 🍄 **Mario Adventure** | Side-scrolling platformer — run, jump, collect stars, stomp enemies | Coordination |
| 🌀 **Maze Explorer** | Navigate procedurally-generated mazes to find the gold star | Spatial reasoning |
| 🐸 **Number Jump** | Tap numbers in order to make the frog jump | Counting |
| 🧠 **Beast Math Maze** | Solve math problems to unlock each jump (Beast Academy inspired) | Addition, subtraction, multiplication |

---

## Project Structure

```
kids-games/
├── index.html          # Homepage — game picker
├── style.css           # Shared styles
├── README.md
└── games/
    ├── mario.html
    ├── maze.html
    ├── number-maze.html
    └── beast-maze.html
```

---

## Run Locally

No install needed — just open `index.html` in any browser.

```bash
git clone https://github.com/KunalJain/kids-games.git
cd kids-games
open index.html   # Mac
# or double-click index.html on Windows
```

---

## Deploy to GitHub Pages

1. Push to the `main` branch
2. Go to repo **Settings → Pages**
3. Set source to `main` branch, root folder
4. Site goes live at `https://kunaljain.github.io/kids-games`

---

## Tech Stack

- **HTML5 Canvas** — all games render on a `<canvas>` element
- **Vanilla JavaScript** — no libraries or frameworks
- **CSS** — shared dark theme + per-game styling
- **GitHub Pages** — free static hosting

---

Made with ❤️ for curious kids everywhere
