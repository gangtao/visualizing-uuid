# Interactive UUID Version Guide 🔢

An educational visualization tool that helps you understand the different UUID (Universally Unique Identifier) versions through interactive diagrams and detailed explanations.

## ✨ Features

- **Interactive Learning**: Explore UUID versions 1, 3, 4, 5, 6, 7, and 8 with detailed breakdowns
- **Visual Diagrams**: D3.js-powered interactive diagrams showing UUID structure
- **Educational Content**: Easy-to-understand explanations with analogies and examples
- **Responsive Design**: Works on desktop and mobile devices
- **Modern Architecture**: Clean separation of HTML, CSS, and JavaScript

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
| v7 | Superstar ⭐ | 2024 | Unix timestamp + random (recommended) |
| v8 | Customizable One | 2024 | Custom/experimental format |

## 🔧 Technologies Used

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Visualization**: D3.js v7.8.5
- **Build Tools**: Yarn, serve
- **Code Quality**: ESLint, Prettier
- **Deployment**: Static files (can be deployed anywhere)

## 🎨 Key Features Explained

### Interactive Diagrams
Each UUID version includes:
- Color-coded segment breakdown
- Connection lines showing data flow
- Hover effects for better interaction
- Responsive design for all screen sizes

### Educational Content
- Simple analogies to explain complex concepts
- Real-world examples and use cases
- Pros and cons comparison
- Timeline demonstrations (for time-based UUIDs)

### Modern Development Workflow
- Separated concerns (HTML/CSS/JS)
- Package management with Yarn
- Development server with hot reloading
- Code formatting and linting
- Production build process

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

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run code quality checks:
   ```bash
   yarn lint
   yarn format
   ```
5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## 📝 Development Notes

### Adding New UUID Versions
To add a new UUID version, update the `versions` object in `script.js`:

```javascript
const versions = {
  // ... existing versions
  newVersion: {
    uuid: "example-uuid-here",
    parts: ["part1", "part2", "part3", "part4", "part5"],
    labels: ["Label1", "Label2", "Label3", "Label4", "Label5"],
    descriptions: ["Desc1", "Desc2", "Desc3", "Desc4", "Desc5"],
    colors: ["#color1", "#color2", "#color3", "#color4", "#color5"],
    title: "Version Name",
    description: "Main description",
    analogy: "Easy-to-understand analogy",
    pros: ["Pro 1", "Pro 2"],
    cons: ["Con 1", "Con 2"]
  }
};
```

### Styling Updates
All styles are in `styles.css` with organized sections:
- Layout and typography
- Component styles
- D3.js specific styles
- Responsive media queries

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- D3.js community for the amazing visualization library
- UUID specification contributors
- The open-source community

---

Made with ❤️ for learning about UUIDs
