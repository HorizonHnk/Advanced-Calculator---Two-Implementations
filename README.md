# Advanced Calculator Implementations 🧮

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/advanced-calculator)
![GitHub license](https://img.shields.io/github/license/yourusername/advanced-calculator)
[![YouTube Channel](https://img.shields.io/badge/YouTube-Tutorial_Series-red)](https://www.youtube.com/playlist?list=PLrZbkNpNVSwzKI0WNMdUQCAWiwTCNefLa)

> Modern calculator implementations in both vanilla JavaScript and React+Vite, featuring responsive design and advanced mathematical operations.

## 📺 Tutorial Series
Complete video tutorials are available on YouTube:
- 📼 [Full Tutorial Playlist](https://www.youtube.com/playlist?list=PLrZbkNpNVSwzKI0WNMdUQCAWiwTCNefLa)
- 🎥 [HTML/CSS/JS Implementation Tutorial](https://youtu.be/p6hScfDr8Y4)
- 🎥 [React/Vite Implementation Tutorial](https://youtu.be/GxrihLwPLSE)

## 🌟 Implementations

### 1. Vanilla JavaScript Version
```javascript
// File structure
/vanilla-js/
  ├── index.html
  ├── styles.css
  └── script.js
```

#### Features:
- 🎯 Pure HTML, CSS, and JavaScript
- 📱 Fully responsive design
- 🎨 Modern UI with animations
- 🧮 Advanced mathematical operations
- 📐 Square root and exponentiation
- 🔄 Clear and delete functions

### 2. React + Vite Version
```javascript
// File structure
/react-vite/
  ├── src/
  │   ├── components/
  │   │   └── AdvancedCalculator.jsx
  │   ├── App.jsx
  │   └── main.jsx
  ├── package.json
  └── vite.config.js
```

#### Features:
- ⚛️ Modern React with Hooks
- 🏃‍♂️ Vite for fast development
- 📱 Cross-platform support
- 🎨 CSS-in-JS styling
- 🧮 State management
- 🔄 Component-based architecture

## 🚀 Quick Start

### Vanilla JavaScript Version
```bash
# Clone the repository
git clone https://github.com/yourusername/advanced-calculator
cd advanced-calculator/vanilla-js

# Open in browser
open index.html
```

### React + Vite Version
```bash
# Navigate to React version
cd react-vite

# Install dependencies
npm install

# Start development server
npm run dev
```

## 📖 Documentation

### Vanilla JavaScript Implementation
```html
<!-- Basic Calculator Structure -->
<div id="calc-container">
    <input id="output-screen" readonly>
    <div id="keypad">
        <!-- Calculator buttons -->
    </div>
</div>
```

### React Implementation
```jsx
// Basic Calculator Component
const AdvancedCalculator = () => {
  const [outputValue, setOutputValue] = useState('');
  
  // Calculator logic
  return (
    <div className="calculator">
      {/* Calculator UI */}
    </div>
  );
};
```

## 🔧 Development

### Prerequisites
- For Vanilla JS: Any modern web browser
- For React version:
  - Node.js ≥ 14.0.0
  - npm or yarn

### Building
```bash
# For React version
npm run build
# or
yarn build
```

## 📝 License
MIT © [Your Name]

## 🤝 Contributing

1. Fork it (https://github.com/HorizonHnk/Advanced-Calculator---Two-Implementations/fork)
2. Create your feature branch (`git checkout -b feature/amazing`)
3. Commit changes (`git commit -am 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing`)
5. Create a Pull Request

## 📺 Related Videos

### Vanilla JavaScript Calculator
[![JavaScript Calculator Tutorial](https://img.shields.io/badge/YouTube-Watch_Tutorial-red)](https://youtu.be/p6hScfDr8Y4)
- Implementation walkthrough
- CSS styling explanation
- JavaScript functionality
- Responsive design techniques

### React Calculator
[![React Calculator Tutorial](https://img.shields.io/badge/YouTube-Watch_Tutorial-red)](https://youtu.be/GxrihLwPLSE)
- React hooks implementation
- State management
- Component structure
- Vite configuration

### Full Series
[![Tutorial Series](https://img.shields.io/badge/YouTube-Full_Series-red)](https://www.youtube.com/playlist?list=PLrZbkNpNVSwzKI0WNMdUQCAWiwTCNefLa)
- Complete tutorial playlist
- Additional tips and tricks
- Comparison between implementations
- Best practices

## 🔗 Important Links
- [YouTube Playlist](https://www.youtube.com/playlist?list=PLrZbkNpNVSwzKI0WNMdUQCAWiwTCNefLa)
- [Vanilla JS Tutorial](https://youtu.be/p6hScfDr8Y4)
- [React Tutorial](https://youtu.be/GxrihLwPLSE)
