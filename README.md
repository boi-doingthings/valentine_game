# 💕 Valentine's Day Game

An interactive, romantic Valentine's Day webpage where you ask your special someone to be your Valentine! Features playful animations, random color themes, and cute characters that change on each visit.

## ✨ Features

- 🎨 **6 Random Color Themes** - Different romantic color palettes on each page load
- 🐻 **4 Cute Characters** - Randomly displays a bear, cat, dog, or bunny
- 💝 **Interactive Buttons** - "Yes" button grows while "No" button shrinks and runs away
- 💬 **Playful Messages** - Funny messages that change as they try to click "No"
- 🎉 **Confetti Celebration** - Epic confetti animation when they say "Yes"
- 💕 **Floating Hearts** - Romantic floating hearts in the background
- 📱 **Mobile Responsive** - Works perfectly on all devices
- 🎭 **Beautiful Typography** - Custom fonts (Pacifico & Poppins) for a polished look

## 🚀 How to Use for Your Own Partner

### Option 1: Quick Customization (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/valentine_game.git
   cd valentine_game
   ```

2. **Edit the name in `index.html`**
   - Open `index.html` in any text editor
   - Find line with: `<h1>Manno, Will you be my Valentine ❤️ ?</h1>`
   - Replace `Manno` with your partner's name
   - Save the file

3. **Deploy to GitHub Pages**
   - Push your changes to GitHub
   - Go to your repository Settings → Pages
   - Select "main" branch as source
   - Your site will be live at: `https://YOUR-USERNAME.github.io/valentine_game/`

4. **Share the link with your partner!** 💕

### Option 2: Local Testing First

1. Clone the repository (same as above)
2. Edit the name in `index.html`
3. Open `index.html` directly in your browser to test
4. Once satisfied, push to GitHub and enable GitHub Pages

## 🎨 Customization Options

### Change the Question Text
Edit line ~302 in `index.html`:
```html
<h1>YourName, Will you be my Valentine ❤️ ?</h1>
```

### Modify Success Message
Edit lines ~313-321 in `index.html`:
```html
<h2>YAY! 🎉💕</h2>
<p>Your custom message here!</p>
```

### Add More Characters
The characters are defined starting at line ~316. You can add more SVG characters to the `characters` array.

### Change Color Themes
Color themes are defined starting at line ~410. Each theme has:
- `bg1` and `bg2`: Background gradient colors
- `primary` and `primaryHover`: Button and accent colors
- `confetti`: Array of confetti colors

## 🛠️ Tech Stack

- Pure HTML, CSS, and JavaScript
- [Canvas Confetti](https://www.npmjs.com/package/canvas-confetti) library
- Google Fonts (Pacifico, Poppins)
- SVG for character illustrations

## 📱 Browser Support

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💝 Credits

Created with love for Valentine's Day! Feel free to customize and share with your special someone.

## 📄 License

Free to use and modify for personal romantic purposes! 💕

---

**Pro Tip**: Test the page by refreshing multiple times to see different characters and color themes before sending to your partner!
