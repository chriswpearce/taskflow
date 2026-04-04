# TaskFlow

A sleek, client-side focus timer and time-tracking app — built as a single HTML file with zero dependencies.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Licence: MIT](https://img.shields.io/badge/Licence-MIT-blue)

## ✨ Features

- **Focus Timer** — Start, pause, and resume a session timer to track the time you spend on tasks.
- **Task Naming** — Label each session with a description of what you're working on.
- **Quick Adjustments** — Add or remove time in preset increments (±5, 15, 30, or 60 minutes), or enter a custom value.
- **Session History** — All completed sessions are saved locally and displayed with daily and all-time totals.
- **CSV Export** — Export your full session history to a CSV file for use in spreadsheets or other tools.
- **Glassmorphism UI** — A modern, dark-themed interface with frosted-glass styling, smooth animations, and responsive layout.
- **Tasky the Mascot** — An animated owl companion who floats, blinks, and reacts to your input. Click Tasky for a surprise! 🦉
- **Fully Offline** — Everything runs in the browser with no server, no build step, and no external dependencies. Data is stored in `localStorage`.
- **Timer Drift Correction** — Automatically corrects the timer if the browser pauses during sleep or idle, so your tracked time stays accurate.

## 🚀 Getting Started

1. **Clone the repository** (or download the HTML file directly):

   ```bash
   git clone https://github.com/chriswpearce/taskflow.git
   ```

2. **Open the file** in any modern web browser:

   ```bash
   open taskflow/Taskflow.html
   ```

   That's it — no installation, no build tools, no dependencies.

## 🎮 Usage

1. Type a task name in the input field (e.g. "Writing report").
2. Press **Start Focus** to begin timing.
3. Press **Stop** to pause, then **Resume** to continue, or **Save Session** to log it.
4. Use the **Quick Adjust** buttons to add or subtract time if needed.
5. View your session history, daily total, and all-time total in the **Recent Sessions** panel.
6. Press **Export CSV** to download your data.
7. Press **Discard Timer** to reset without saving.

> 💡 **Tip:** Click on Tasky the owl mascot — there may be a hidden game waiting for you!

## 🛠️ Technology

TaskFlow is a self-contained single-file web application:

| Layer      | Technology                     |
| ---------- | ------------------------------ |
| Structure  | HTML5                          |
| Styling    | CSS3 (custom properties, glassmorphism, animations) |
| Logic      | Vanilla JavaScript (ES6+)      |
| Storage    | Browser `localStorage`         |
| Typography | [Inter](https://rsms.me/inter/) (loaded via Google Fonts) |

No frameworks. No bundlers. No package managers. Just one file.

## 📂 Project Structure

```
taskflow/
├── Taskflow.html   # The entire application
├── README.md       # This file
└── LICENCE         # MIT Licence
```

## 🤝 Contributing

Contributions are welcome! If you'd like to improve TaskFlow:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/my-improvement`).
3. Commit your changes (`git commit -m "Add my improvement"`).
4. Push to your branch (`git push origin feature/my-improvement`).
5. Open a pull request.

Please ensure any changes maintain the single-file architecture.

## 📝 Licence

This project is licensed under the [MIT Licence](LICENCE).

## 👤 Author

**Chris Pearce**

---

Made with ☕ and focus.
