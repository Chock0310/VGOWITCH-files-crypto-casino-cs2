# 🎰 VGOWitch.com — Casino Game Source

Welcome to the official **VGOWitch.com** casino source code!  
This package includes a full-featured web casino system with both **Slots** and **Originals Games** (custom-built in-house).  
It’s designed for speed, scalability, and an immersive player experience.

---

## 🕹️ Game Modules Included

### 🎲 Originals
These are custom “in-house” casino games, optimized for fairness and instant play:
- **Mines** — Reveal gems, avoid bombs, and cash out strategically.  
- **Crash** — Ride the multiplier and cash out before it crashes.  
- **Dice** — Roll and predict outcomes with adjustable odds.  
- **Towers** — Climb the tower to the top without hitting traps.  
- **Unbox** — Mystery case-opening game with animated reveals.  
- **Battles** — Player-vs-player wagered rounds with RNG-based outcomes.  
- **Vault** — Secure in-site wallet with deposit/withdraw locking features.

### 🎰 Slots
- Fully integrated slot game engine compatible with external providers.  
- Supports **Drakon Gator API** and other modern providers.  
- Customizable RTP, reels, and win animations.

---

## 🧩 Tech Stack
- **Frontend:** Vue.js (Shuffle-style design)  
- **Backend:** Node.js / Express  
- **Database:** MongoDB (via Mongoose models)  
- **Real-time:** Socket.io for live bets and updates  
- **Templating:** EJS or Vue single-file components (SFC)  
- **Payments:** OxaPay & Crypto gateways (BTC, ETH, USDT, etc.)

---

## ⚙️ Installation Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/vgowitch.com.git
   cd vgowitch.com
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```


3. **Start the script**
   ```bash
   npm run dev
   ```


Your casino should now be live at:  
➡️ **http://localhost**

---

## 💰 Game Providers
Easily integrate your slot provider by configuring:
```
/backend/routes/drakon.js
```


---

## 🧠 Notes
- All games use server-seeded randomization for provable fairness.  
- Frontend styled similar to **Shuffle.com** for a modern and clean casino experience.  
- The codebase supports theme customization (colors, gradients, and assets).  

---

## 🆘 Need Help?
If you need **help with installation, configuration, or custom game integration**,  
feel free to reach out on **Telegram**:  
👉 **[t.me/mhjakan](https://t.me/mhjakan)**

---

## ⚡ License
This source is for educational and private development use only.  
Redistribution or resale without permission is prohibited.
