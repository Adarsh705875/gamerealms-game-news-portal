<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e0e0e,50:ff0055,100:00ffff&height=220&section=header&text=GameRealms&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Game%20news%2C%20characters%20and%20upcoming%20releases%20in%20one%20neon%20hub&descAlignY=58&descSize=18" width="100%" />

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Forms](https://img.shields.io/badge/Google_Forms-7248B9?style=for-the-badge&logo=googleforms&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

### [🚀 **Live Demo**]( https://adarsh705875.github.io/gamerealms-game-news-portal/)

</div>

> ⚠️ **Disclaimer:** GameRealms is an independent fan and learning project. It is **not affiliated with or endorsed by** any game studio or publisher. All game titles, characters and trademarks belong to their respective owners. News, release dates and "leak" articles on the site are **sample content** for demonstration and are not official information.

---

## 📸 Preview

<!-- Upload a screenshot or GIF to /screenshots and un-comment: -->
<!-- ![GameRealms preview](./screenshots/preview.gif) -->

*Add a screenshot or GIF of the homepage here.*

---

## 📖 About

**GameRealms** is a gaming-themed front-end website where players can browse iconic game characters, read gaming news and blog posts, and check a countdown-style list of upcoming releases. It focuses on a bold neon look, smooth animations and a fully responsive layout, built from scratch without frameworks.

## ✨ Features

| | Feature | Details |
|---|---|---|
| 🎬 | **Video hero section** | Full-screen looping video background with a glowing neon headline |
| 🧑‍🎤 | **Character showcase** | Alternating character cards with hover zoom and glow, plus voice lines that play on hover |
| 🕹️ | **Upcoming releases** | Game cards generated from a JavaScript data array, with trailer embeds and launch countdowns |
| 📰 | **News and blog feed** | Article sections with embedded YouTube videos and animated RGB glow cards |
| ✨ | **Animated UI** | Particle canvas, RGB gradient dividers, glitch-style headings and a sparkle "Read More" button that cycles colors |
| 🔐 | **Login / Signup modal** | Animated tabbed modal (front-end UI only, no backend) |
| 💬 | **Feedback form** | Sends email and message to a Google Form, with an animated thank-you confirmation |
| 📱 | **Responsive design** | Layouts adapt for tablets and phones |

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3: Flexbox, keyframe animations, gradients, media queries |
| Logic | Vanilla JavaScript: DOM manipulation, Canvas API, Date API |
| Fonts | Google Fonts (Orbitron, Press Start 2P) |
| Forms | Google Forms |
| Hosting | GitHub Pages |

## 📁 Project Structure

```
gamerealms-gaming-website/
├── index.html          # Main page: markup, styles and scripts
├── StyleSheet.css      # Extra styles
├── more-news.html      # News page linked from the homepage
├── assets/
│   ├── videos/         # hero and character background videos
│   ├── images/         # backgrounds and character art
│   └── audio/          # character voice clips
└── README.md
```

> Media files are not included in this repository where they would raise copyright concerns. Replace them with your own assets to run the full experience.

## 🏃 Run locally

```bash
git clone https://github.com/Adarsh705875/gamerealms-gaming-website.git
cd gamerealms-gaming-website
python -m http.server 8000
```

Then open `http://localhost:8000`.

## 🛠️ Customize

- **Games list:** edit the `games` array near the bottom of `index.html` (title, date, description, trailer URL).
- **Characters:** duplicate a `.character` block and change the image, name and text.
- **Feedback form:** replace the Google Form `action` URL and `entry.` field IDs with your own form.
- **Colors:** the neon palette uses `#ff0055`, `#00ffff`, `#ff00ff` and `#00ff99`. Search and replace to re-theme.

## ⚠️ Known Issues

- Some trailer embeds are placeholders and need real YouTube links.
- Release dates are sample data, and the countdown text needs a fix for games that have already launched.
- Login and Signup are UI only. No accounts are created.
- Large videos can slow the first load on mobile.

## 🔮 Roadmap

- [ ] Move CSS and JS into separate files
- [ ] Load games and news from a JSON file or API
- [ ] Working authentication with a backend
- [ ] Search and filter for games
- [ ] Dark and light themes
- [ ] Lazy-load videos for faster mobile performance

## 🎓 What I Learned

- Building a complex responsive layout without a framework
- CSS animations, gradients and layered backgrounds
- Rendering UI from JavaScript data
- Handling form submission to Google Forms
- Managing media assets and performance for a media-heavy site

## 👤 Author

**Adarsh Kadam**: Game Developer · AI/ML Engineer · Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarsh-kadam)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Adarsh705875)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adarshkadam06@gmail.com)

<div align="center">

⭐ If you like this project, consider starring the repo!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ffff,50:ff0055,100:0e0e0e&height=100&section=footer" width="100%" />

</div>
