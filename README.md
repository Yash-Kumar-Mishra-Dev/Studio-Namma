# Studio Namma

Studio Namma is an interactive creative studio landing page and portfolio application built using modern web development practices. The application incorporates dynamic custom cursor tracking, video hover interactions, responsive layout design, and a dedicated Express.js static file server.

---

## Features

- **Interactive Playground Grid**: Hover over portfolio elements (MATERA, CHANCE, SILVR, INTRAMUROS) to play context-aware video previews and dynamic text overlays.
- **Custom Cursor System**: Dual-layer mouse movement tracking with video cursor container and adaptive pointer indicators.
- **Navigation Overlay**: Fullscreen slide-out menu system managed via CSS transitions and JavaScript state controls.
- **Dark Aesthetic & Typography**: Dark UI aesthetic integrated with Google Fonts (Anton) and optimized video assets.
- **Express Web Server**: Pre-configured Node.js Express server to serve static assets and handle local development hosting on port 5500.

---

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Assets**: WebP graphics, HTML5 MP4 Video stream rendering
- **Typography**: Google Fonts (Anton)

---

## Project Structure

```text
Studio-Namma/
├── index.html            # Primary HTML structure and document outline
├── style.css             # Main stylesheet including layout models and keyframe rules
├── script.js             # Client-side JavaScript handling UI state and DOM events
├── server.js             # Node.js server configuration serving static files
├── package.json          # Dependency manifest and project execution scripts
├── .gitignore            # Version control exclusions
└── assets/               # Media assets directory (MP4 videos and WebP images)
```

---

## Getting Started

### Prerequisites

Ensure [Node.js](https://nodejs.org/) (v14.0 or later) is installed on your system.

### Installation and Execution

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Yash-Kumar-Mishra-Dev/Studio-Namma.git
   cd Studio-Namma
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   npm start
   ```

4. **Access the application**:
   Open a web browser and navigate to `http://localhost:5500`.

---

## License

This project is distributed under the ISC License.
