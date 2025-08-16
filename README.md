# Nerdy CMD 💻

A retro-styled interactive command-line interface built with pure HTML, CSS, and JavaScript. Experience the nostalgia of classic terminals with modern web functionality.

![Terminal Interface](https://img.shields.io/badge/Interface-Terminal-green)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Features

- **Authentic Terminal Experience**: Classic black background with green text, just like the good old days
- **Interactive Command Processing**: Real-time command execution with proper feedback
- **Project Portfolio Integration**: Showcase your projects with built-in navigation
- **Smooth Animations**: Loading spinners and transitions for enhanced UX
- **Responsive Design**: Works seamlessly across all devices
- **No Dependencies**: Pure vanilla JavaScript - no frameworks required

## 🎯 Demo

Open `nerdy-cmd.html` in your browser and start typing commands! The interface activates with any keypress and provides an authentic terminal experience.

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nerdy-cmd.git
   cd nerdy-cmd
   ```

2. **Open in browser**
   ```bash
   open nerdy-cmd.html
   # or simply double-click the file
   ```

That's it! No build process, no dependencies, no hassle.

## 🎮 Usage

### Available Commands

| Command | Description |
|---------|-------------|
| `help` | Display all available commands |
| `projects` | List your portfolio projects |
| `clear` | Clear the terminal screen |
| `1` or `portfolio website` | Open Portfolio Website |
| `2` or `school management system` | Open School Management System |
| `nam` | Easter egg command 🎵 |

### Getting Started

1. Press any key to activate the terminal
2. Type `help` to see all available commands
3. Use `projects` to browse your portfolio
4. Type project numbers or names to open them

## 🛠️ Customization

### Adding New Projects

Edit the `projects` object in the JavaScript section:

```javascript
const projects = {
    1: { name: 'Your Project Name', link: 'https://yourproject.com' },
    2: { name: 'Another Project', link: 'https://anotherproject.com' },
    3: { name: 'New Project', link: 'https://newproject.com' }, // Add here
};
```

### Styling Customization

Key CSS variables you can modify:

```css
body {
    background-color: #000; /* Terminal background */
    color: #0f0;           /* Primary text color */
}

.nerdy-text {
    color: #0ff;           /* Highlight color */
}
```

### Adding Custom Commands

Extend the `processCommand` function:

```javascript
case 'your-command':
    appendOutput('Your custom response');
    break;
```

## 🎨 Design Philosophy

- **Minimalist**: Clean, distraction-free interface
- **Nostalgic**: Authentic retro terminal aesthetics
- **Functional**: Every element serves a purpose
- **Accessible**: Keyboard-driven navigation
- **Fast**: Lightweight with no external dependencies

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request

### Development Guidelines

- Keep it vanilla - no frameworks or libraries
- Maintain the retro aesthetic
- Test across different browsers
- Follow the existing code style
- Add comments for complex functionality

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**William Berge Groensberg**
- Created: April 29, 2025
- Last Updated: August 11, 2025

## 🙏 Acknowledgments

- Inspired by classic DOS and Unix terminals
- Built with modern web standards
- Special thanks to the retro computing community

## 📊 Project Stats

- Lines of Code: ~150
- File Size: ~4KB
- Load Time: <100ms
- Browser Support: All modern browsers

---

*Built with ❤️ and a healthy dose of nostalgia*

**Happy coding! 🚀**
