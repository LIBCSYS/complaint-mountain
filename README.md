# 🏔️ Complaint Mountain — The Electronic Board Game

> *A fine place to be unhappy — together.*

**Version 1.0Delta**

A charming, fully self-contained **pass-and-play electronic board game**. Margaret and the perpetually-dissatisfied residents of Complaint Village race up Complaint Mountain — rolling dice, drawing Complaint Cards, surviving the dreaded Roundabout, and lodging as many complaints as possible along the way.

First to the summit wins. The biggest complainer is crowned **Chief Complainer of the Mountain**.

**No build step. No dependencies. No tracking. Just open `index.html`.**

## ▶️ Play

- **Live demo:** **https://complaintmountain.com** (the full Complaint Mountain world; game at [/game](https://complaintmountain.com/game))
- **Static mirror:** https://libcsys.github.io/complaint-mountain/
- **Local:** clone this repo and open `index.html` in any modern browser. That's it.

## 🎲 How to play

1. Choose **2–6 residents** — Margaret, Bryan, Edith, Nigel, Cynthia, or Derek — and pass the device around.
2. On your turn, tap **Roll**; your token climbs the winding mountain road.
3. Land on a space:
   - 📝 **Complaint Card** — draw a (frequently petty) twist of fate.
   - ☕ **The Café** — pause for a moan and a flat white. +1 point.
   - 🔄 **The Roundabout** — engineering's greatest mystery. Anything can happen.
4. **First to the summit wins.** Most Complaint Points earns the title of Chief Complainer.

## ✨ Features

- **Single HTML file**, vanilla JavaScript — zero dependencies, zero build tooling.
- Crisp **SVG mountain board** with character tokens that glide along the road.
- Elegant dusk palette, *Fraunces* + *Inter* typography, smooth animations.
- Fully **responsive** — plays on phone or desktop.
- Local **pass-and-play** — no accounts, no server, no internet required after load.
- **Accessible** — keyboard-playable character selection and dialogs, screen-reader-friendly game log, honours `prefers-reduced-motion`.

## 🛠️ Tech

Plain HTML / CSS / JavaScript. Board geometry is computed along an SVG path with `getPointAtLength`. Web fonts are loaded from Google Fonts via CDN (optional — it degrades gracefully offline).

## 📜 License

[MIT](LICENSE) — do what you like, have fun, complain freely.

---

*Built with Claude. Part of the Complaint Mountain world at [complaintmountain.com](https://complaintmountain.com).*
