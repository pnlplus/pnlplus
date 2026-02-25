# PNL+

Create stunning, custom PNL cards — right from your terminal.

PNL+ is a web-based tool that lets terminal users generate fully customized **PNL (Profit & Loss) cards**. Choose from a library of preset videos or upload your own, then overlay your PNL data directly on the video — all inside your browser.

---

## Features

- **Video Selection** — Browse and select from a curated set of background videos
- **Custom Video Upload** — Upload your own video to use as the card background
- **PNL Overlay** — Overlay your profit/loss data on top of the video in real time
- **Terminal-Friendly Workflow** — Designed with CLI users in mind
- **Browser-Based** — No heavy installs required; everything runs in the browser

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- A modern web browser

### Installation

```bash
# Clone the repository
git clone https://github.com/pnlplus/pnlplus.git

# Navigate into the project directory
cd pnlplus

# Install dependencies
npm install
```

### Running the App

```bash
npm run dev
```

Then open your browser and go to `http://localhost:3000`.

---

## How It Works

1. **Launch** the app via the terminal using `npm run dev`
2. **Select a video** from the preset library or **upload your own** video file
3. **Enter your PNL data** (ticker, profit/loss amount, percentage change, etc.)
4. The app **overlays** your PNL information onto the video in real time
5. **Export or share** your custom PNL card

---

## Project Structure

```
pnlplus/
├── public/          # Static assets and preset videos
├── src/
│   ├── components/  # UI components (video picker, overlay, etc.)
│   ├── pages/       # App pages/routes
│   └── utils/       # Helper functions
├── package.json
└── README.md
```

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Made with love by the PNL+ team
