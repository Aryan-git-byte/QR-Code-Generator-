# QR Code Generator 🎨

A modern, responsive web application that converts URLs and text into customizable QR codes with color options and download functionality.

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

[Live Demo]([https://aryan-git-byte.github.io/qr-code-generator](https://qrcodegenerator241.netlify.app/))

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, flexbox, and grid
- **JavaScript (ES6+)**: Interactive functionality and QR generation
- **QRious Library**: High-quality QR code generation
- **Responsive Design**: Mobile-first approach

## 📦 Installation

### Quick Start
1. Clone this repository:
   ```bash
   git clone https://github.com/aryan-git-byte/qr-code-generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd qr-code-generator
   ```
3. Open `index.html` in your web browser

### GitHub Pages Deployment
1. Fork this repository
2. Go to Settings > Pages in your forked repository
3. Select source as "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://your-username.github.io/qr-code-generator`

## 📱 Usage

1. **Enter Content**: Type any URL or text in the input field
2. **Choose Colors**: Use the color pickers to customize QR code and background colors
3. **Generate**: Click "Generate QR" button or press Enter
4. **Download**: Click "Download" to save as PNG image

### Example Content to Try:
- `https://github.com/aryan-git-byte`
- `https://google.com`
- `Hello World!`
- `mailto:contact@example.com`
- `tel:+1234567890`

## 🔧 Customization

### Changing QR Code Size
Modify the size parameter in the JavaScript:
```javascript
const qr = new QRious({
    element: canvas,
    value: link,
    size: 256, // Change this value (default: 256px)
    foreground: foregroundColor,
    background: backgroundColor,
    level: 'M'
});
```

### Custom Color Themes
Edit default colors in the HTML:
```html
<input type="color" id="foregroundColor" value="#000000" />
<input type="color" id="backgroundColor" value="#ffffff" />
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
└── README.md           # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/NewFeature`)
3. **Commit** your changes (`git commit -m 'Add NewFeature'`)
4. **Push** to the branch (`git push origin feature/NewFeature`)
5. **Open** a Pull Request

### Ideas for Contributions:
- 📊 Different QR code error correction levels
- 🎨 More color themes and presets
- 📱 PWA (Progressive Web App) functionality
- 🔍 QR code scanner/reader feature
- 📁 Batch QR code generation
- 🎭 Logo embedding in QR codes
- 🌍 Multiple language support

## 🔮 Roadmap

- [ ] QR code reader/scanner functionality
- [ ] Batch generation for multiple URLs
- [ ] Logo embedding feature
- [ ] Dark/light theme toggle
- [ ] QR code templates and presets
- [ ] Mobile app version

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Aryan**
- GitHub: [@aryan-git-byte](https://github.com/aryan-git-byte)

## 🙏 Acknowledgments

- [QRious](https://github.com/neocotic/qrious) - Excellent QR code generation library
- [CDNJS](https://cdnjs.com/) - Reliable CDN hosting
- Modern web design inspiration

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
