# ♔ Interactive Chess Game ♛

A fully functional, embed-ready chess game built with pure HTML, CSS, and JavaScript. Perfect for demos, educational purposes, or integration into websites.

## ✨ Features

### 🎮 Core Gameplay
- **Complete Chess Rules**: All standard chess pieces with proper movement validation
- **Turn-based Play**: Alternating white and black moves
- **Move Validation**: Prevents illegal moves and highlights valid options
- **Visual Feedback**: Selected pieces and valid moves are highlighted
- **Move History**: Tracks all moves with standard chess notation

### 🎨 Customization
- **6 Color Schemes**: Classic, Gray, Orange, Green, Blue, and Purple
- **Board Flipping**: View the game from either player's perspective
- **Responsive Design**: Works on desktop, tablet, and mobile devices

### 📊 Game Management
- **Winner Tracking**: Stores the last 10 game winners with timestamps
- **Undo Function**: Step back through moves
- **New Game**: Start fresh at any time
- **Persistent Storage**: Winners are saved locally

### 🔗 Embedding & Sharing
- **Embed-Ready**: Copy iframe code for easy integration
- **Shareable URL**: Works as a standalone application
- **CORS-Friendly**: No external dependencies that could cause CORS issues

## 🚀 Quick Start

1. **Open the Game**: Simply open `index.html` in any modern web browser
2. **Start Playing**: Click on pieces to select them, then click on valid squares to move
3. **Customize**: Use the color picker in the sidebar to change board appearance
4. **Share**: Click "Copy Embed Code" to get the iframe code for embedding

## 🎯 How to Play

### Basic Controls
- **Select Piece**: Click on any piece of your color
- **Make Move**: Click on a highlighted square to move
- **Valid Moves**: Green squares show valid moves, red squares show captures
- **Turn Indicator**: The game info shows whose turn it is

### Game Features
- **Pawn Promotion**: Pawns automatically promote to queens when reaching the opposite end
- **Move History**: View all moves in the sidebar
- **Winner Tracking**: See the last 10 winners with dates
- **Board Flip**: Click "Flip Board" to view from the opposite perspective

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and modern structure
- **CSS3**: Flexbox, Grid, gradients, and animations
- **Vanilla JavaScript**: No frameworks or external libraries
- **Local Storage**: Persistent winner tracking

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

### File Structure
```
TestAppForAI/
├── index.html          # Main application file
├── README.md          # This documentation
└── LICENSE            # License information
```

## 🔧 Customization

### Adding New Color Schemes
To add a new color scheme, modify the `colorSchemes` object in the JavaScript:

```javascript
const colorSchemes = {
    // ... existing schemes
    custom: { light: '#yourLightColor', dark: '#yourDarkColor' }
};
```

### Embedding in Other Sites
Use the provided embed code or create your own iframe:

```html
<iframe src="path/to/index.html" width="800" height="600" frameborder="0"></iframe>
```

### Styling Modifications
All styles are embedded in the HTML file for easy modification. Key CSS classes:
- `.chessboard`: Main game board
- `.square`: Individual board squares
- `.game-section`: Main game area
- `.sidebar`: Control panel and info

## 🎨 Color Schemes Available

1. **Classic**: Traditional brown chess board colors
2. **Gray**: Modern gray and white theme
3. **Orange**: Warm orange and brown theme
4. **Green**: Natural green theme
5. **Blue**: Cool blue theme
6. **Purple**: Royal purple theme

## 📱 Responsive Design

The game automatically adapts to different screen sizes:
- **Desktop**: Full-size board with sidebar
- **Tablet**: Scaled board with responsive layout
- **Mobile**: Compact layout with touch-friendly controls

## 🔒 Privacy & Data

- **No External APIs**: All functionality is self-contained
- **Local Storage Only**: Winner data is stored locally in the browser
- **No Tracking**: No analytics or data collection
- **CORS-Free**: No external requests that could cause CORS issues

## 🚀 Deployment

### Local Development
1. Clone or download the files
2. Open `index.html` in a web browser
3. Start playing immediately

### Web Hosting
1. Upload `index.html` to any web server
2. Access via URL
3. Share the URL or embed code

### GitHub Pages
1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `https://username.github.io/repository-name`

## 🤝 Contributing

This is a standalone application, but you can:
- Fork the code for your own projects
- Modify colors, styles, or functionality
- Add new features like AI opponents
- Improve the chess engine logic

## 📄 License

This project is open source and available under the MIT License.

## 🎯 Use Cases

- **Educational**: Teach chess to students
- **Demo**: Showcase web development skills
- **Integration**: Embed in existing websites
- **Entertainment**: Casual chess games
- **Testing**: UI/UX testing and development

---

**Enjoy playing chess! ♔♛**
