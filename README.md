# Rubik's Cube Simulator

A beautiful, interactive 3D Rubik's Cube simulator built with HTML5, CSS3, and JavaScript using Three.js.

## Features

- **3D Interactive Cube**: Fully rotatable Rubik's Cube with smooth animations
- **Multiple Themes**: Choose from different color schemes (Cube, Erno, Dust, Camo, Rain)
- **Custom Theme Editor**: Create your own color combinations
- **Timer**: Built-in timer to track solve times
- **Statistics**: Keep track of your best times and solve statistics
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Modern dark UI with cyan accents

## How to Use

1. **Scramble**: Click anywhere on the screen to scramble the cube
2. **Solve**: Use mouse/touch to rotate the cube faces
3. **Timer**: The timer starts automatically when you begin solving
4. **Settings**: Access preferences and theme editor via the menu buttons

### Controls
- **Mouse**: Click and drag to rotate the cube
- **Touch**: Touch and drag on mobile devices
- **Face Rotation**: Click on a face to rotate it

## Technologies Used

- **Three.js**: 3D graphics and WebGL rendering
- **JavaScript (ES6+)**: Game logic and interactions
- **HTML5**: Structure and canvas
- **CSS3**: Styling and animations

## Getting Started

### Option 1: Run Locally
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start solving!

### Option 2: Use a Local Server
For the best experience, run with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Then open http://localhost:8000 in your browser
```

## Customization

### Themes
The cube supports multiple built-in themes:
- **Cube**: Classic bright colors
- **Erno**: Professional color scheme
- **Dust**: Earthy tones
- **Camo**: Military camouflage
- **Rain**: Cool blue tones

### Custom Colors
Use the theme editor to create your own color combinations:
1. Go to Preferences → Theme
2. Click on any cube face to select and modify colors
3. Use the HSL sliders to adjust hue, saturation, and lightness

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

Built with [Three.js](https://threejs.org/) - A JavaScript 3D library.