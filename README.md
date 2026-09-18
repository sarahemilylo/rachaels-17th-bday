# 🎂 Happy Birthday Rachael!

![HTML](https://img.shields.io/badge/Language-HTML5-orange.svg)
![CSS](https://img.shields.io/badge/Style-CSS3-blue.svg)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow.svg)
![Interactive](https://img.shields.io/badge/Interactive-Yes-ff69b4.svg)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Made With Love](https://img.shields.io/badge/Made%20with-❤️-ff69b4.svg)

An interactive digital birthday card created for **Rachael**. 🎀

<img width="2871" height="1461" alt="image" src="https://github.com/user-attachments/assets/cb4b292f-d810-47c2-b10c-c7502adcba99" />

---

## ✨ Features

### 🎀 Interactive Card Opening

The experience begins with the closed birthday card.

- Click the card to open it
- Smooth opening animation
- Transition from the cover to the inside spread
- Handmade scrapbook-inspired design

---

### 💌 Hidden Birthday Letter

A personalized birthday message is tucked inside an envelope.

- Click the envelope to open it
- Letter slides out onto the card
- Read the full birthday message
- Click away to return the letter to the envelope

---

### 🎂 Interactive Birthday Cake

The birthday cake isn't just decorative — the candles are interactive!

- Individual candle flames
- Clickable candles
- Flames disappear when blown out
- Original illustrated/collage cake aesthetic is preserved

---

### 🕯️ Blow Out the Candles

Each flame behaves as its own interactive element.

```text
🔥 🔥 🔥
│  │  │
│  │  │
🎂🎂🎂
```

Click the candles:

```text
      🔥
│  │  │
│  │  │
🎂🎂🎂
```

Until...

```text
│  │  │
│  │  │
🎂🎂🎂
```

All the candles are out!

---

### ✨ Make a Wish

After every candle has been blown out, the card reveals a special:

> **Make a Wish ✨**

moment to complete the birthday experience.

---

### 🎉 Celebration Effects

Interactive animations help make important moments feel more special.

These include:

- Smooth transitions
- Candle animations
- Card-opening animation
- Envelope interaction
- Celebration effects
- Subtle movement throughout the experience

---

## 🎨 Design Style

The project follows a handmade digital scrapbook aesthetic.

Design elements include:

- 🎀 Bows and ribbons
- 💌 Paper envelopes
- 📝 Handwritten notes
- 🎂 Illustrated birthday cake
- 📸 Personal photographs
- ✨ Layered collage elements
- 📰 Paper textures
- 🌸 Soft pastel colours

The goal was to make the website feel less like a traditional webpage and more like a **real handmade birthday card brought to life**.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the birthday card |
| CSS3 | Styling and animations |
| JavaScript | Interactive elements |
| PNG Assets | Scrapbook and collage elements |
| CSS Transforms | Card-opening animations |
| JavaScript Events | Candle and envelope interactions |

---

## 📂 Project Structure

```text
rachael-birthday-card/
│
├── index.html
│
├── README.md
│
└── images/
│   ├── card-cover.png
│   ├── card-inside.png
│   ├── envelope.png
│   ├── letter.png
│   ├── cake.png
│   ├── candle-flame-1.png
│   ├── candle-flame-2.png
│   ├── candle-flame-3.png
│   └── decorations/
│       ├── bows.png
│       ├── ribbons.png
│       └── scrapbook-elements.png
```

---

## 🎮 User Experience

The birthday card follows a simple interactive story:

```text
Birthday Card Cover
        │
        │ click
        ▼
   Card Opens
        │
        ▼
Inside Birthday Card
     ┌──┴──┐
     │     │
     ▼     ▼
 Envelope  Cake
     │      │
     ▼      ▼
  Letter  Candles
            │
            ▼
      Blow Them Out
            │
            ▼
       Make a Wish ✨
```

---

## 💌 Envelope Interaction

```text
Closed Envelope
      │
      │ click
      ▼
Envelope Opens
      │
      ▼
Letter Slides Out
      │
      ▼
Read Birthday Message
      │
      │ click away
      ▼
Letter Returns
```

This makes the birthday message feel like something Rachael actually discovers rather than something immediately displayed on screen.

---

## 🎂 Candle Interaction

Each candle flame is separated from the cake artwork so that it can behave independently.

```javascript
candle.addEventListener("click", () => {
    flame.classList.add("blown-out");
});
```

Once all candle flames have been extinguished, the next part of the birthday experience is revealed.

---

## 📱 Responsive Design

The card is designed to work across different screen sizes.

- Desktop
- Laptop
- Tablet
- Mobile

The interactive elements scale while maintaining the scrapbook-style layout.

---

## 🌟 Project Goals

The project was designed around three main ideas:

**Personal**  
Use real memories and handmade-looking elements rather than a generic birthday template.

**Interactive**  
Give Rachael things to discover, click, open, and interact with.

**Memorable**  
Turn a simple birthday message into a small experience she can explore.

---

## 💖 About This Project

This project was created as a digital birthday gift for **Rachael**.

It combines a traditional birthday card with web development to create something that feels personal, playful, and handmade.

From opening the card...

to discovering the letter...

to blowing out the candles...

the entire experience was designed specifically for her birthday. 🎂

---

## 👩‍💻 Created By

**Sarah**

---

### 🎈 Happy Birthday Rachael! 🎈

Hope you have the best birthday ever! 🎂✨
