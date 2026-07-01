# 💳 Pricing Table

A clean, fully responsive pricing table built with **pure HTML and CSS** — no frameworks, no JavaScript. Powered by CSS Flexbox and a single media query for responsiveness.

<img width="1638" height="965" alt="Screenshot 2026-07-01 125631" src="https://github.com/user-attachments/assets/8d60eae8-9e30-4fd2-a6cf-0c90676dc0c1" />


## 🌐 Live Demo

🔗 [View Live Demo](#) <!-- Replace with your GitHub Pages link after deployment -->

## ✨ Features

- **Three-tier pricing layout** — Basic, Standard, and Premium plans with clear visual hierarchy
- **Flexbox-based structure** — Cards are centered and evenly spaced using `display: flex`
- **Fully responsive** — Cards stack vertically on smaller screens (`max-width: 1250px`) via a media query
- **Feature comparison icons** — ✅ for included features, 🚫 for excluded ones
- **Custom typography** — Uses the [Sono](https://fonts.google.com/specimen/Sono) Google Font for a distinctive monospace look
- **Zero dependencies** — No CSS frameworks or JS libraries required

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Markup structure |
| CSS3 (Flexbox) | Layout & responsiveness |
| Google Fonts | Typography (Sono) |

## 📊 Pricing Plans

| Plan | Price | Storage | Users | Support |
|---|---|---|---|---|
| **Basic** | $9.99/month | 10GB | 1 | 🚫 None |
| **Standard** | $19.99/month | 50GB | 5 | ✅ Phone & Email |
| **Premium** | $49.99/month | 100GB | 10 | ✅ 24/7 |

## 📁 Project Structure

flexbox-pricing-table/
├── index.html          # Main HTML file with embedded CSS
├── screenshots/
│   └── preview.png      # Project preview image
└── README.md            # Project documentation

## 📱 Responsive Behavior

The layout uses a CSS media query to switch from a horizontal row to a vertical stack on smaller viewports:

```css
@media (max-width: 1250px) {
  .pricing-container {
    flex-direction: column;
  }
}
```

## 🎯 What I Learned

- Structuring flexible, evenly-spaced layouts with `display: flex`, `align-items`, and `justify-content`
- Building responsive designs using media queries with `flex-direction`
- Styling reusable UI card components with consistent spacing and typography
- Importing and applying custom Google Fonts


**Your Name**
- GitHub: [@your-username](https://github.com/your-username)

---
