# 🎂 Happy 19nd Birthday aditi ! - Interactive Birthday Experience  

[![Live Demo](https://img.shields.io/badge/🎉%20Live%20Demo-Click%20Here-blueviolet?style=for-the-badge)](https://patrick-paul.github.io/happybirthday/)

A personalized, interactive birthday greeting webpage featuring smooth animations, microphone-enabled candle blowing, confetti effects, and a beautiful timeline experience.

## ✨ Features

- **Elegant Card Opening Animation** - Beautiful 3D flip card introduction
- **GSAP Timeline Animations** - Smooth, choreographed text and element transitions
- **Interactive Candle Blowing** - Blow into your microphone to blow out birthday candles (with click fallback)
- **Dynamic Visual Effects** - Floating balloons, confetti, and fireworks
- **Background Music Control** - Toggle music on/off with visual controls
- **Fully Responsive** - Works beautifully on desktop and mobile devices
- **Custom Cursors** - Themed birthday cake and candle cursors throughout

## 🚀 How to Use

1. **Clone Repository**

   ```bash
   # Clone this repository
   git clone https://github.com/patrick-paul/happybirthday

   # Navigate into the repository
   cd happybirthday

   # Open with your text editor
   code .
   ```

2. **Customize the Content**


   - Update the name "ADITI" throughout the HTML
   - Modify the birthday message in the text box section
   - Add your own birthday song to `./music/hbd.mpeg`
   - Update custom cursor images in `./img/` if desired

3. **Run Locally**

   Open `index.html` with Live Server in VS Code, or simply open it in your browser.

4. **Deployment**

   Deploy easily with:
   - **GitHub Pages**: Enable in repository Settings → Pages
   - **Netlify**: Drag and drop the folder
   - **Vercel**: Connect your repository

## 🎨 Customization Guide

### Key Elements to Personalize:

- **Line 11**: Update page title
- **Lines 152-160**: Modify card front message
- **Lines 161-168**: Update card back message
- **Line 176**: Change recipient name
- **Line 184**: Update birthday number
- **Lines 188-195**: Personalize birthday message
- **Line 220**: Update profile picture source
- **Line 223**: Modify birthday wish heading

### Colors & Theme:

The design uses a vibrant gradient color scheme:
- Pink: `#FF4DA6`
- Yellow: `#FFD54F`
- Cyan: `#00E5FF`

Modify these in the CSS to match your preferred theme.

## 🎵 Audio Requirements

Place your birthday song file at `./music/hbd.mpeg`. The music:
- Plays automatically after card opening
- Can be toggled with the floating music control
- Stops automatically when the song ends

## 📁 Project Structure

```
happybirthday/
├── index.html          # Main HTML file
├── img/
│   ├── Aditi.jpg        # Profile picture
│   ├── hat.svg        # Birthday hat
│   ├── birthday-cake.png    # Cursor image
│   └── birthday-candle.png  # Cursor image
└── music/
    └── hbd.mpeg       # Birthday song
```

## 🌟 Key Features Explained

### Microphone Candle Blowing
The experience detects microphone input to blow out candles:
1. Checks for existing microphone permission
2. Pauses timeline and music if permission needed
3. Requests permission on user interaction
4. Falls back to click mode if permission denied
5. Resumes experience smoothly after permission granted

### Performance Optimizations
- Asset preloader with progress bar
- Efficient animation cleanup
- Optimized confetti and balloon generation
- Proper microphone stream management

## 📝 Contributing

Have ideas to make this more special? Feel free to:
- Submit a pull request
- Open an issue for feature requests
- Share your customized versions

## 🙏 Credits

Built with love using:
- [GSAP](https://greensock.com/gsap/) - Animation library
- [Google Fonts](https://fonts.google.com/) - Typography
- Vanilla JavaScript - Core functionality


---

Made with 💖 by Aryan gupta

---

*Remember: The best gift is the time and effort you put into making someone feel special!*
