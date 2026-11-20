# ✦ CharacterGuesser

**How well do you really know your favourite fictional worlds?**

CharacterGuesser is a fan-made character trivia game inspired by Wordle. Identify a mystery character using clues about their identity, attributes, affiliations, and first appearance.

**[Play CharacterGuesser](https://ventusblitz.github.io/)**

---

## 🎮 About the Game

Each round gives you one randomly selected mystery character. Your objective is to identify them within **20 guesses**.

After every guess, the game provides colour-coded feedback to help you narrow down the answer.

### Colour Guide

| Colour | Meaning |
|---|---|
| 🟩 Green | Correct match |
| 🟨 Yellow | Partial match or related information |
| 🟥 Red | Incorrect match |

Some multi-value attributes, such as affiliations, support partial matching. Shared groups and organisations are highlighted to help you narrow down the answer.

---

## ✨ Features

- **20 guesses per round** — A challenging but forgiving limit.
- **Multiple fictional universes** — Switch between the currently available character worlds.
- **Random character selection** — A new mystery character every round.
- **Live autocomplete** — Find characters as you type.
- **Colour-coded feedback** — Green, yellow, and red clues.
- **Partial attribute matching** — Shared affiliations and other supported multi-value attributes are highlighted.
- **Detailed character attributes** — Compare multiple aspects of each character.
- **Responsive interface** — Play on desktop, tablet, or mobile.
- **Cyberpunk-inspired design** — Dark purple backgrounds, neon accents, and themed scrollbars.
- **Instant replay** — Start another round as soon as you finish.

---

## 🌌 Available Universes

| Universe | Status |
|---|---|
| Wizarding World | 🟢 Available |
| Middle-earth | 🟢 Available |
| A Song of Ice and Fire | 🟡 Work in Progress |

### 🪄 Wizarding World

The playable Wizarding World database includes characters from:

- The seven original *Harry Potter* novels.
- The *Fantastic Beasts* film series.

Character clues include:

- **Species** — The character's species or nature.
- **Gender** — The character's gender.
- **House** — Their Hogwarts house, where applicable.
- **Blood Status** — Their wizarding blood status.
- **Affiliations** — Groups, organisations, families, or other associations.
- **First Appearance** — The book or film in which they first appeared.

### 🧙 Middle-earth

The Middle-earth game uses the same core guessing mechanics, with a separate set of Tolkien-inspired character attributes:

- **Race / Being** — The character's race or nature.
- **Gender** — The character's gender.
- **Realm / Origin** — Their realm, homeland, or place of origin.
- **House / Lineage** — Their family, house, or lineage.
- **Affiliations** — Groups, peoples, kingdoms, and other associations.
- **Age** — Their known or approximate age.
- **First Appearance** — The earliest published work in which the character appears.

The Middle-earth database is a **curated roster** drawn from Tolkien's published legendarium. It includes material from works such as *The Hobbit*, *The Lord of the Rings*, *The Silmarillion*, and other published writings. It is not claimed to be an exhaustive index of every named or referenced character.

### ⚔️ A Song of Ice and Fire

A Song of Ice and Fire is planned as a separate playable universe. Its character database and universe-specific attributes are still in progress.

---

## 🛠️ Built With

CharacterGuesser is a lightweight, browser-based project built using:

- **HTML5** — Page structure and content.
- **CSS3** — Layout, animations, responsive design, and visual styling.
- **Vanilla JavaScript** — Game logic, character databases, autocomplete, and feedback system.
- **Google Fonts** — Orbitron and Rajdhani typography.

There are no frameworks, backend servers, or build tools required to run the current version.

---

## 🚀 Run Locally

You can run CharacterGuesser directly in your browser.

1. Clone the repository:

   ```bash
   git clone https://github.com/VentusBlitz/ventusblitz.github.io.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

That's it! No installation or additional dependencies are required.

---

## 🌐 GitHub Pages Deployment

CharacterGuesser can be hosted for free using GitHub Pages.

1. Create a repository named `VentusBlitz.github.io`.
2. Upload the project files.
3. Make sure the main HTML file is named `index.html`.
4. Open the repository's **Settings → Pages**.
5. Select **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)` folder.
7. Save your settings.

Your website will be available at:

**https://ventusblitz.github.io/**

---

## 📁 Project Structure

```text
CharacterGuesser/
│
├── index.html       # Main game, styling, logic, and character databases
└── README.md        # Project documentation
```

The current implementation keeps the game's HTML, CSS, JavaScript, and character data together in a single HTML file for simplicity.

---

## 🗺️ Roadmap

- [x] Build the core guessing game.
- [x] Add the Wizarding World character database.
- [x] Implement colour-coded attribute matching.
- [x] Add autocomplete suggestions.
- [x] Add a 20-guess limit.
- [x] Create a responsive neon-themed interface.
- [x] Add Middle-earth as a separate playable universe.
- [ ] Expand and verify the character databases.
- [ ] Add A Song of Ice and Fire.
- [ ] Introduce additional universes.
- [ ] Continue improving character clues and database accuracy.

---

## ⚠️ Disclaimer

CharacterGuesser is an independent, fan-made trivia project created for entertainment and educational purposes.

It is not affiliated with, endorsed by, or officially connected to Warner Bros., J. K. Rowling, Middle-earth Enterprises, George R. R. Martin, or any other respective copyright or trademark holders.

All fictional characters, universes, and associated trademarks belong to their respective owners.

---

## 👨‍💻 Creator

**VentusBlitz**

A fan-made Trivia game by VentusBlitz.

[GitHub Profile](https://github.com/VentusBlitz)

---

*Test your knowledge. Trust your instincts. Guess the character.*
