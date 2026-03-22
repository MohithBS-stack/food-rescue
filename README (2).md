# 🍱 FoodRescue India

> A surplus food redistribution platform connecting restaurants, households and caterers with NGOs and individuals — reducing food waste and hunger simultaneously.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Leaflet](https://img.shields.io/badge/Leaflet.js-199900?style=flat&logo=leaflet&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

**UN SDGs addressed:**
🟡 SDG 2 — Zero Hunger &nbsp;|&nbsp; 🟢 SDG 12 — Responsible Consumption &nbsp;|&nbsp; 🔵 SDG 11 — Sustainable Cities

---

## 🚀 Live Demo

👉 **[View Live on GitHub Pages](https://YOUR-USERNAME.github.io/food-rescue)**

---

## ✨ Features

- 🗺️ **Interactive Leaflet map** — colour-coded pins by food category, no API key needed
- 📝 **Post surplus food** — restaurants, households, caterers can list food in 30 seconds
- 🙋 **Claim listings** — NGOs and individuals claim food before it expires
- ⏱️ **Expiry timers** — urgent listings highlighted in orange, auto-expire
- 📍 **GPS location** — one-click location capture for posting
- 💾 **localStorage persistence** — listings saved in browser, survive page refresh
- 📊 **Live stats** — available, claimed, total portions counter
- 🔔 **Zero dependencies** — no npm, no build step, just open in browser

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Map | Leaflet.js 1.9 (free, no API key) |
| Tiles | OpenStreetMap |
| Storage | Browser localStorage |
| Frontend | Vanilla JS ES Modules |
| Fonts | Nunito (Google Fonts) |
| Hosting | GitHub Pages |

---

## ⚙️ Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/food-rescue.git
cd food-rescue
python3 -m http.server 8080
# Open http://localhost:8080
```

> For the single-file version, just open `food-rescue-single.html` directly in your browser — no server needed!

---

## 📁 Project Structure

```
food-rescue/
├── index.html               ← App shell
├── style.css                ← Warm green theme
├── food-rescue-single.html  ← All-in-one file (GitHub Pages ready)
├── README.md
└── js/
    ├── config.js            ← Categories, sample data, settings
    ├── data.js              ← Listings store + localStorage
    ├── map.js               ← Leaflet map + custom markers
    ├── listings.js          ← Feed, post form, claim modal
    └── main.js              ← Entry point
```

---

## 🌱 Why I Built This

India wastes ~68 million tonnes of food annually while 190 million people go hungry. The gap isn't food production — it's redistribution. Surplus food from restaurants and events expires before it reaches anyone in need, simply because there's no easy way to connect donors with recipients.

FoodRescue makes that connection instant — post in 30 seconds, claim with one tap.

Built as **Weekend Project #2 of 12** — each project tackles a real-world problem aligned with UN Sustainable Development Goals.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<p align="center">Made with 🍱 and zero tolerance for food waste</p>
