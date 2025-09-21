# Interactive UUID Version Guide 🔢

An educational visualization tool that helps you understand the different UUID (Universally Unique Identifier) versions through interactive diagrams and detailed explanations.

## ✨ Features

- **Interactive Learning**: Explore UUID versions 1, 3, 4, 5, 6, 7, and 8 with detailed breakdowns
- **Visual Diagrams**: D3.js-powered interactive diagrams showing UUID structure
- **Educational Content**: Easy-to-understand explanations with analogies and examples

## 🚀 Quick Start

### Prerequisites

- Node.js (>= 14.0.0)
- Yarn (>= 1.22.0)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/gangtao/visualizing-uuid.git
cd visualizing-uuid
```

2. Install dependencies:
```bash
yarn install
```

3. Start the development server:
```bash
yarn start
```

4. Open your browser and navigate to `http://localhost:3000`

## 📁 Project Structure

```
visualizing-uuid/
├── index.html          # Main HTML file
├── styles.css          # All styling and CSS
├── script.js           # JavaScript functionality and data
├── package.json        # Project configuration and dependencies
├── .gitignore         # Git ignore rules
├── yarn.lock          # Yarn lockfile
└── README.md          # Project documentation
```

## 🛠️ Available Scripts

### Development
- `yarn start` or `yarn dev` - Start development server on port 3000
- `yarn build` - Build project for production (copies files to `dist/`)
- `yarn clean` - Remove build artifacts

### Code Quality
- `yarn lint` - Run ESLint for code quality checks
- `yarn format` - Format code with Prettier

## 🎯 UUID Versions Covered

| Version | Name | Year | Description |
|---------|------|------|-------------|
| v1 | Time Traveler | 1990s | MAC address + timestamp based |
| v3 | Name-Based Helper | 2005 | MD5 hash based |
| v4 | Random Champion | 2005 | Completely random |
| v5 | Improved Name-Helper | 2005 | SHA-1 hash based |
| v6 | Organizer | 2024 | Reordered v1 for better performance |
| v7 | Superstar | 2024 | Unix timestamp + random (recommended) |
| v8 | Customizable One | 2024 | Custom/experimental format |


## 🚀 Deployment

The project generates static files that can be deployed to any web server:

1. Build the project:
```bash
yarn build
```

2. Deploy the `dist/` folder to your hosting platform:
   - GitHub Pages
   - Netlify
   - Vercel
   - Any static hosting service


