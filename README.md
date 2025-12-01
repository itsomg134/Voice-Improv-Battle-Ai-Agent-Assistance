
#  Voice Improv Battle – AI-Powered Improv Game Show (Day 10)

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-purple)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![JavaScript](https://img.shields.io/badge/ES6-F7DF1E?logo=javascript)
![Voice](https://img.shields.io/badge/Voice-Interactive-ff69b4?logo=googleassistant)
![Murf Falcon](https://img.shields.io/badge/Murf-Falcon_TTS%2FSTT-orange)
![License](https://img.shields.io/badge/License-MIT-green)

**A fast-paced, fully voice-driven improv game where the AI host gives you hilarious, chaotic, dramatic improv scenes — and you must perform them live.
Built for the #MurfAIVoiceAgentsChallenge.**

[Features](#-features) • [Gameplay](#-how-the-game-works) • [Architecture](#-architecture) • [Setup](#-quick-start) • [Demo](#-demo-video) • [Author](#-author)

</div>

---

<img width="1280" height="720" alt="Brown and Beige Modern AI Features" src="https://github.com/user-attachments/assets/5560c628-a871-4ced-84b7-b8dbb05e6417" />


---

## 🎭 Overview

**Voice Improv Battle** is an AI-powered improv stage in your browser.
You speak → the AI Host sets a scene → you act → it judges you → next round begins.

Inspired by shows like:
*Whose Line Is It Anyway*, *Improv Tonight*, and *Comedy Bang Bang* — but fully voice-controlled.


## 🎥 Demo Video

📎 Day 10 showcase demo (replace with your link):
(https://drive.google.com/file/d/17eurE2bKxnOKHO0rpldInMtE7TZ4rC2q/view?usp=sharing)

The AI Host:

✔ Creates fun improv scenarios
✔ Plays multiple characters
✔ Judges your performance
✔ Tracks your score
✔ Keeps the tone energetic and funny
✔ All through **voice**, using Murf Falcon

A hilarious, high-energy voice game show you can play solo or turn into a party game.

---

## 🚀 Core Idea

### **A voice-first improv performance game.**

Each round, the AI Host:

1. Sets a creative or absurd improv scenario
2. Assigns you a role
3. Gives you a conflict or twist
4. Asks you to *perform it live with your voice*
5. Judges your performance and updates your score
6. Moves to the next round
7. Ends by presenting your finale scoreboard

Everything is hands-free.

---

## ⭐ Features

### 🎙 Fully Voice-Controlled

Hosted + performed entirely with Murf Falcon STT/TTS.

### 🤹 Wild Improv Scenarios

The AI generates rich, funny, unexpected setups every round.

### 🧑‍🤝‍🧑 Host Persona

Energetic, dramatic, comedic — customizable.

### 🏆 Scoreboard

Each round gives:

* Creativity score
* Humor score
* Character consistency score

Total score updates automatically.

### 🔄 Session Engine

Runs:

* Start show
* Up to `max_rounds`
* Finale celebration

### 🔊 Built on Day 9’s Voice Runtime

VAD, turn detection, TTS/STT pipeline all included.

---

## 🎮 How the Game Works

### Example turn:

> 🎙 **Host**:
> “You are a barista who discovers that your coffee machine is actually a portal to another dimension.
> Perform the scene in 10 seconds.
> **Begin… now!**”

> 🎤 **You**:
> *“Welcome to Om’s Café… wait—why is the coffee glowing blue?”*

> 🎙 **Host**:
> “Ha! Loved the energy.
> Creativity: 8/10
> Delivery: 9/10
> Comedy: 7/10
> **Total Score:** 24 points!”

And then the next round begins.

---

## 🧠 Architecture

```
/Voice-Improv-Battle
│
├── src/
│   ├── improv_agent.ts        # Main game engine
│   ├── host_persona.ts        # Host personality + tone
│   ├── scene_generator.ts     # Improv prompt generation
│   ├── score_engine.ts        # Scoring logic (creativity/comedy/etc)
│   ├── tools/                 # Voice tools (TTD, STT, start_show...)
│   │   ├── start_show.ts
│   │   ├── run_round.ts
│   │   └── finish_show.ts
│
├── ui/
│   ├── components/
│   │   └── Waveform.tsx
│   ├── App.tsx
│   └── index.html
│
├── public/
├── package.json
└── README.md
```

---

## 🎤 Voice Tools (Built Into the Agent)

### `start_show(name, max_rounds)`

Initializes host, scoreboard, and intro narration.

### `run_round(prompt)`

Generates scenario → listens → judges you → updates score.

### `finish_show()`

Final scoreboard + outro performance.

---

## 📁 Sample Round Template

```json
{
  "role": "Time-traveling detective",
  "location": "1920s jazz club",
  "conflict": "Your future self tries to stop you",
  "tone": "dramatic but hilarious"
}
```

---

## ⚙️ Quick Start

### 1. Clone

```bash
git clone https://github.com/yourusername/voice-improv-battle
cd voice-improv-battle
```

### 2. Install

```bash
npm install
```

### 3. Run

```bash
npm run dev
```

The UI will open automatically.
Press 🎤 **Start Game** → improv begins.

---

## 🖥️ Screenshots

*(Add your screenshots here)*

* Home screen
* Voice visualizer (ECG waveform)
* Live round
* Scoreboard

---



---

## 🔮 Future Plans

* Multiplayer improv battle
* Audience reaction meter
* Duo improv mode
* Adaptive host personality
* Custom scenario packs (Holiday, Sci-Fi, Bollywood Comedy, etc.)
* Live streaming mode

---

## 👨‍💻 Author

**Om Gedam**

* GitHub: **@itsomg134**
* Email: **[omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)**
* X: **@omgedam**
* LinkedIn: *Om Gedam*
* Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)

Built with ⚡ Murf Falcon + 💜 love for improvisation.

---

If you want, I can also generate:
✅ The **banner image** for GitHub
✅ A **compact version** of this README
✅ A **project logo**
Just tell me!
