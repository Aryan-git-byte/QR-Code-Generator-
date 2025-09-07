# QR Code Generator 🎨

A modern, responsive web application that converts URLs and text into customizable QR codes with color options and download functionality.

![QR Code Generator Preview](https://via.placeholder.com/600x400/667eea/ffffff?text=QR+Code+Generator)

## ✨ Features

- **🔗 Universal Input**: Convert any URL or text into a QR code
- **🎨 Color Customization**: Choose custom colors for QR code and background using hex color picker
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **⬇️ Download Option**: Save generated QR codes as PNG images
- **⚡ Real-time Preview**: QR code updates automatically when colors change
- **🎯 Modern UI**: Beautiful gradient design with glassmorphism effects
- **⌨️ Keyboard Support**: Generate QR codes by pressing Enter
- **🔄 Smooth Animations**: Elegant transitions and hover effects

## 🚀 Demo

[Live Demo](https://your-username.github.io/qr-code-generator) *(Replace with your actual GitHub Pages URL)*

## 📸 Screenshots

### Desktop View
![Desktop View](https://via.placeholder.com/800x500/764ba2/ffffff?text=Desktop+View)

### Mobile View
![Mobile View](https://via.placeholder.com/300x600/667eea/ffffff?text=Mobile+View)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, flexbox, and grid
- **JavaScript (ES6+)**: Interactive functionality and QR generation
- **QRious Library**: High-quality QR code generation
- **Responsive Design**: Mobile-first approach

## 📦 Installation

### Option 1: Direct Download
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/qr-code-generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd qr-code-generator
   ```
3. Open `index.html` in your web browser

### Option 2: GitHub Pages
1. Fork this repository
2. Go to Settings > Pages
3. Select source as "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://your-username.github.io/qr-code-generator`

### Option 3: Local Server
If you prefer running a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server installed globally)
npx http-server

# Using PHP
php -S localhost:8000
```

## 📱 Usage

1. **Enter Content**: Type any URL or text in the input field
2. **Choose Colors**: Use the color pickers to customize:
   - QR Code color (default: black)
   - Background color (default: white)
3. **Generate**: Click "Generate QR" button or press Enter
4. **Download**: Click "Download" to save as PNG image

### Example URLs to Try:
- `https://github.com`
- `https://google.com`
- `mailto:contact@example.com`
- `tel:+1234567890`
- Any text content

## 🔧 Customization

### Changing Default Colors
Edit the default values in the HTML:
```html
<input type="color" id="foregroundColor" value="#000000" />
<input type="color" id="backgroundColor" value="#ffffff" />
```

### Modifying QR Code Size
Change the size parameter in the JavaScript:
```javascript
const qr = new QRious({
    element: canvas,
    value: link,
    size: 256, // Change this value
    // ...
});
```

### Styling Modifications
The CSS uses custom properties for easy theming. Main color variables:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --background-color: rgba(255, 255, 255, 0.95);
    --text-color: #333;
}
```

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Structure

```
qr-code-generator/
│
├── index.html          # Main HTML file with embedded CSS and JS
├── README.md           # Project documentation
└── LICENSE             # License file (optional)
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions:
- 📊 Add different QR code error correction levels
- 🎨 More color themes and presets
- 📱 PWA (Progressive Web App) functionality
- 🔍 QR code scanner/reader feature
- 📁 Batch QR code generation
- 🎭 Different QR code styles and patterns
- 📈 Analytics and usage tracking
- 🌍 Internationalization (i18n)

## 🐛 Known Issues

- None currently reported

## 🔮 Roadmap

- [ ] Add QR code reader/scanner functionality
- [ ] Implement batch generation for multiple URLs
- [ ] Add more customization options (logo embedding, rounded corners)
- [ ] Create mobile app version
- [ ] Add QR code templates and presets
- [ ] Implement dark/light theme toggle

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)
- Twitter: [@your-twitter](https://twitter.com/your-twitter)

## 🙏 Acknowledgments

- [QRious](https://github.com/neocotic/qrious) - For the excellent QR code generation library
- [CDNJS](https://cdnjs.com/) - For reliable CDN hosting
- Color inspiration from modern web design trends
- Icons and design patterns from contemporary UI/UX practices

## ⭐ Show Your Support

If you found this project helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs or issues
- 💡 Suggesting new features
- 🤝 Contributing to the code

---

<div align="center">
  <strong>Built with ❤️ and modern web technologies</strong>
</div>
