# 🍅 PomodoClock

> A dark, distraction-free Pomodoro timer. No install. Just open and focus.

---

## Quick Start

1. Download `PomodoClock.html`
2. Double-click it — opens in any browser
3. Hit ▶ and get to work

---

## Features

- 🎯 **Three modes** — Focus (25 min), Short Break (5 min), Long Break (15 min)
- 🔴 **Animated ring** — glowing progress arc that shifts color per mode
- 🍅 **Session tracker** — 5 tomato icons fill up as you complete each set
- 🔔 **Desktop notifications** — alerts you when any timer finishes
- 🔁 **Keep timer on switch** — toggle to let background timers keep running
- 📌 **Tab title countdown** — see the timer without switching windows
- ⚡ **Zero dependencies** — single HTML file, works fully offline

---

## Controls

| Button | Action |
|--------|--------|
| ▶ / ⏸ | Start / pause |
| ↺ | Reset current timer |
| ⏭ | Skip to next mode |
| Mode tabs | Switch between Focus, Short Break, Long Break |
| Keep on Switch toggle | When ON, inactive timers keep counting in the background (green dot = still running) |

---

## Chrome Extension

A toolbar extension is also available in `PomodoClock-extension.zip`.

**To install:**
1. Unzip the file
2. Go to `chrome://extensions`
3. Enable **Developer mode** (top-right toggle)
4. Click **Load unpacked** → select the unzipped folder
5. The 🍅 icon appears in your toolbar

---

## Tech

- Vanilla HTML / CSS / JS — no frameworks
- Single file, ~23 KB
- Uses the [Web Notifications API](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API)
- Session data resets on page reload (in-memory only)
