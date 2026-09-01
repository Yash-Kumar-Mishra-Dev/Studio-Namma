# Studio Namma 🎨✨

**Studio Namma** is an interactive, high-craft creative studio landing page and portfolio website built with modern web technologies. It features smooth custom cursor interactions, video hover effects, dynamic font styling, and an Express static server setup.

---

## 🚀 Features

- 🎥 **Interactive Playground Grid**: Hover over portfolio blocks (MATERA, CHANCE, SILVR, INTRAMUROS) to reveal preview videos with custom animated labels.
- 🎯 **Custom Video Cursor**: Dynamic mouse-following cursor box and custom pointer states that dynamically change context on hover.
- 🍔 **Slide-out Navigation Menu**: Clean overlay menu toggled via smooth CSS transitions.
- 🌙 **Modern Dark Aesthetic**: Styled with Google Fonts (`Anton`), smooth grid layouts, and immersive video integration.
- ⚡ **Lightweight Express Server**: Express.js server setup for quick local hosting and static asset serving.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla ES6+)
- **Backend / Web Server**: Node.js, Express.js
- **Typography**: Google Fonts (Anton)

---

## 📂 Project Structure

```text
Studio-Namma/
├── index.html            # Main HTML document with layout & sections
├── style.css             # Custom CSS styling, layouts, and animations
├── script.js            # Interactive JS logic (cursor effects, menu toggle, video hover)
├── server.js            # Express server hosting static assets on port 5500
├── package.json          # Node dependencies & npm scripts
├── .gitignore            # Git ignore configuration
└── assets/               # Video and WebP image media assets
    ├── block1.webp / block2.mp4 ...
    ├── cursorvid.mp4
    └── matera-highlight-2.mp4
```

---

## 🚦 Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation & Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Yash-Kumar-Mishra-Dev/Studio-Namma.git
   cd Studio-Namma
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the local server**:
   ```bash
   npm start
   ```
   Or run directly with Node:
   ```bash
   node server.js
   ```

4. **View in browser**:
   Open [http://localhost:5500](http://localhost:5500) in your web browser.

---

## 📜 License  

This project is  a licensed under the [ISC License](LICENSE).
