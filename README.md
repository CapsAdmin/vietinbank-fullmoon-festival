# 🌙 Moon Festival Invitation Website

A beautiful, interactive invitation website for kids' Moon Festival celebrations with parallax effects and animations.

## 🚀 Features

- **Parallax Background Effects**: Interactive mouse-responsive parallax using the Parallax.js library
- **Static Content Overlay**: Main invitation text stays readable while background elements move with parallax
- **Custom Font**: Cherry Bomb One font for playful headers
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Animated Elements**: Floating moon, twinkling stars, and glowing text effects
- **Kid-Friendly Content**: Colorful design with fun activities and easy-to-read information

## 📝 Easy Date Customization

To change the invitation date, simply edit the `index.html` file:

1. Open `index.html` in any text editor
2. Find this line (around line 142):
   ```html
   <div class="event-date">
       Saturday, October 14th, 2025
   </div>
   ```
3. Change the date to your desired event date
4. Save the file

**The date is clearly marked with a comment in the CSS for easy identification!**

## 🖼️ Required Images

Make sure to add these image files to the same directory as `index.html`:

- `background.jpg` - Main parallax background image
- `animal1.png` - First animal character (positioned left side)
- `animal2.png` - Second animal character (positioned right side)  
- `animal3.png` - Third animal character (positioned center-bottom)
- `logo.png` - Your logo (displayed in bottom-right corner)

## 🎨 Customization Tips

### Colors
- Primary gold: `#ffd700` (moon and title glow)
- Accent pink: `#ff6b6b` (subtitle and buttons)
- Purple gradient: `#667eea` to `#764ba2` (event details)

### Text Content
- Edit the invitation text in the `.invitation-card` section
- Modify activities in the `.activity-list`
- Update event details (time, location, dress code, etc.)

### Parallax Settings
Adjust parallax behavior in the JavaScript section:
- `scalarX/Y`: Movement sensitivity (default: 8.0)
- `limitX/Y`: Movement limits (default: 50)
- `frictionX/Y`: Easing amount (default: 0.1)

## 🌐 GitHub Pages Deployment

### Method 1: Automatic Deployment
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" 
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at: `https://yourusername.github.io/repositoryname`

### Method 2: Manual Setup
1. Create a repository named `yourusername.github.io`
2. Upload the files directly to the root
3. Your site will be available at: `https://yourusername.github.io`

## 📱 Mobile Optimization

The site is fully responsive with:
- Scaled-down fonts for mobile screens
- Adjusted animal sizes for smaller displays
- Single-column layout for activity lists
- Touch-friendly button sizes

## 🛠️ Technical Requirements

- Modern web browser with JavaScript enabled
- Internet connection (for Google Fonts and Parallax.js CDN)
- No server-side requirements - pure static HTML/CSS/JS

## 🎪 Customizing Activities

To modify the activity list, edit the `.activity-list` section:

```html
<ul class="activity-list">
    <li>🥮 Your Custom Activity</li>
    <li>🏮 Another Fun Activity</li>
    <!-- Add more activities as needed -->
</ul>
```

## 🌟 Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 RSVP Functionality

The current RSVP button shows a simple alert. For real RSVP collection, you can:
1. Link to a Google Form
2. Add a mailto: link
3. Integrate with form services like Formspree or Netlify Forms

## 🎨 Image Recommendations

- **background.jpg**: 1920x1080px, night sky or mystical landscape
- **animal*.png**: 200x200px transparent PNGs, cute cartoon animals
- **logo.png**: 100x100px transparent PNG, your event logo

## 💡 Performance Tips

- Optimize images (WebP format recommended)
- Consider lazy loading for better performance
- Test on various devices and screen sizes

---

**Enjoy your magical Moon Festival celebration! 🌙✨**