# 🏏 Cricket Scorer

A fully-featured, mobile-first cricket scoring web app built as a single HTML file. Set up a match, enter player names, and score ball-by-ball in real time — with live stats, over history, fall of wickets, and a PIN-protected umpire mode for spectators.

---

## ✨ Features

- 🏟️ **Match setup** — team names, player rosters (2–11 players), overs (2 to 50/ODI), and toss
- 📊 **Live scoreboard** — runs, wickets, overs, and Current Run Rate (CRR) updated on every ball
- 🎯 **2nd innings target chase** — shows Target, Runs Needed, Balls Left, and Required Run Rate (RRR)
- ⚡ **Ball-by-ball scoring** — dot, 1, 2, 3, 4, 6, Wide, No Ball, Bye, and Wicket buttons
- 🧠 **Wicket modal** — select dismissal type and incoming batter on each wicket
- 👤 **Live batter stats** — Runs, Balls, 4s, 6s, and Strike Rate for both batters at the crease
- 🏹 **Live bowler stats** — Overs, Maidens, Runs, Wickets, and Economy
- 🔵 **Ball log** — colour-coded balls for the current over (4s, 6s, wickets, wides, no-balls)
- 📈 **Over history** — runs scored per completed over
- 💥 **Fall of Wickets** — records each dismissal with score and over
- ↩️ **Undo** — revert the last ball entry
- 🔒 **Umpire PIN system** — set a 4-digit PIN at setup; spectators see the scoreboard but scoring controls are PIN-locked
- 👁️ **Spectator / Umpire view toggle** — fixed top tab bar to switch between views
- 📱 **Mobile-first & responsive** — optimised for phones, works on desktop too

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML / CSS / Vanilla JS | Entire app — no frameworks, no dependencies |
| Google Fonts (Barlow Condensed + Rajdhani) | Typography |

No npm, no build tools, no backend. One file, open and play.

---

## 📁 Project Structure

```
├── cricket-scoreboard.html    # Complete app in a single self-contained file
```

---

## 🚀 Usage

### Option 1 — Open locally
Just double-click `index.html` in any browser. No server needed.

### Option 2 — Host it online

- **[Vercel]([https://pages.github.com/](https://cricket-score-card-swart.vercel.app/))** 

---

## 🏁 How to Score a Match

1. **Setup screen** — enter team names, player names, overs, and an optional umpire PIN
2. **Toss** — select who won the toss and chose to bat/bowl
3. **Select striker, non-striker, and bowler** from the dropdowns
4. **Tap scoring buttons** — dot, 1, 2, 3, 4, 6, W, Wd, NB, Bye
5. On a **wicket**, a modal asks for dismissal type and the next batter coming in
6. After the 1st innings ends, tap **Start 2nd Innings** — the target is automatically set
7. The match ends with a result banner showing the winner and margin (runs or wickets)

---

## 🔒 Umpire PIN Mode

If a PIN is set during setup:
- The scoreboard is **publicly visible** to spectators by default
- Scoring controls are hidden behind a **4-digit PIN pad**
- Switch between **Spectator** and **Umpire** views using the tab bar at the top
- Ideal for streaming the scoreboard on a shared screen while the umpire scores on the same device

---

## 🎨 Colour Coding

| Colour | Meaning |
|---|---|
| 🟡 Gold | 6s, run rate stats, key highlights |
| 🟢 Green | 4s, economy, progress bar |
| 🔴 Red | Wickets, danger overs |
| 🔵 Blue | Wides & No Balls |
| ⚪ White | Standard runs |

---

## 📄 License

Open source — free to use, fork, and adapt for your own matches.
