# 🪐 Orbit Focus

A space-themed productivity app that helps you stay focused, organize tasks, and track completed study sessions.

Built with **HTML, CSS, and vanilla JavaScript** in a single file.

## ✨ Features

- **Focus timer:** 25-minute work sessions.
- **Break timer:** 5-minute rest sessions.
- **Timer controls:** Start, pause, resume, and reset.
- **Animated orbit:** A planet animation that moves while the timer runs.
- **Task board:** Add, complete, and delete tasks.
- **Saved progress:** Tasks and completed focus sessions persist using localStorage.
- **Responsive layout:** Adapts to mobile and desktop screens.
- **Accessibility:** Keyboard focus indicators, labeled controls, and reduced-motion support.

## 🚀 Getting Started

1. Download or clone this repository.
2. Open `index.html` in your browser.

No installation, dependencies, or API keys are required.

### Optional: Run a Local Server

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then visit **http://localhost:8000**.

## 🎯 How to Use

1. Add a task to your mission board.
2. Select **Focus** and click **Start mission**.
3. Pause or resume whenever needed.
4. Mark tasks complete as you finish them.
5. After a focus session, select **Rest** to start a break.

Completed focus sessions increase your mission count. Breaks do not start automatically.

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- Browser localStorage

## 📁 Project Structure

```text
orbit-focus/
├── index.html
└── README.md
```

All styles and JavaScript are included in `index.html`.

## 🎨 Customization

Edit the CSS variables in `:root` to change the colors.

To adjust session lengths, update the focus and break durations in the JavaScript. Also update the button labels and initial timer display to match.

## 💾 Data Storage

Tasks and completed session counts are saved locally in your browser. They are not uploaded or synchronized across devices.

Clearing browser storage removes saved progress. The active timer resets when the page reloads.

## 📝 Notes

- Keep the page open while a session runs.
- Completion messages appear on the page; there are no sound alerts or system notifications.
- Browser storage must be available to retain progress after closing the page.
