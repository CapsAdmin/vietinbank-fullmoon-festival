# ⚡ Quick Customization Guide

## 🗓️ Change Event Date (EASY!)

**Location in `index.html`**: Line ~165

```html
<div class="event-date">
    Saturday, October 14th, 2025    <!-- CHANGE THIS DATE -->
</div>
```

## 📍 Event Details

**Location in `index.html`**: Lines ~168-185

```html
<div class="event-info">
    <div>
        <strong>🕕 Time</strong><br>
        6:00 PM - 9:00 PM          <!-- CHANGE TIME -->
    </div>
    <div>
        <strong>📍 Location</strong><br>
        Magic Garden Park          <!-- CHANGE VENUE -->
    </div>
    <div>
        <strong>👕 Dress Code</strong><br>
        Pajamas & Cozy Clothes     <!-- CHANGE DRESS CODE -->
    </div>
    <div>
        <strong>🎒 Bring</strong><br>
        Blanket & Pillow           <!-- CHANGE WHAT TO BRING -->
    </div>
</div>
```

## 🎪 Activities List

**Location in `index.html`**: Lines ~190-197

```html
<ul class="activity-list">
    <li>🥮 Moon Cake Making</li>      <!-- CHANGE ACTIVITIES -->
    <li>🏮 Lantern Decorating</li>    <!-- ADD YOUR OWN -->
    <li>🎵 Sing Along Songs</li>      <!-- KEEP OR REMOVE -->
    <li>📚 Story Time</li>
    <li>🎨 Face Painting</li>
    <li>⭐ Star Gazing</li>
</ul>
```

## 🎨 Main Titles

**Location in `index.html`**: Lines ~145-146

```html
<h1 class="main-title">🌙 Moon Festival 🌙</h1>    <!-- MAIN TITLE -->
<h2 class="subtitle">Magic Night Party!</h2>        <!-- SUBTITLE -->
```

## 💌 Invitation Text

**Location in `index.html`**: Lines ~150-153

```html
<p class="invitation-text">
    🌟 You're invited to the most magical night of the year! 🌟<br>
    Join us for an enchanted Moon Festival celebration where we'll dance under the stars, 
    enjoy delicious treats, and create memories that will last forever!
</p>
```

## 🎨 Color Scheme (Advanced)

Change these CSS variables in the `<style>` section:

```css
/* Main Colors */
--gold: #ffd700;        /* Moon and title glow */
--pink: #ff6b6b;        /* Subtitle and buttons */
--purple: #667eea;      /* Event details background */
--white: #ffffff;       /* Card backgrounds */
```

## 🖱️ Parallax Settings (Advanced)

**Location in `index.html`**: JavaScript section (~420-440)

```javascript
var parallaxInstance = new Parallax(scene, {
    scalarX: 6.0,        // Mouse sensitivity (higher = more movement)
    scalarY: 6.0,        // Vertical sensitivity  
    limitX: 40,          // Max movement distance
    limitY: 40,          // Max vertical movement
    frictionX: 0.15,     // Smoothness (lower = smoother)
    frictionY: 0.15      // Vertical smoothness
});
```

## 🌙 Emoji Guide

Feel free to change or add emojis throughout:
- 🌙 🌟 ⭐ ✨ 🌠 (space theme)
- 🎉 🎪 🎨 🎵 🎭 (party theme) 
- 🥮 🏮 🧧 🎋 🐰 (festival theme)
- 👨‍👩‍👧‍👦 👶 🧸 🎈 🎁 (kids theme)

## 🔧 Easy Edits Checklist

- [ ] Change event date
- [ ] Update time and location
- [ ] Modify activity list
- [ ] Add your images (see IMAGE_REQUIREMENTS.md)
- [ ] Test in browser
- [ ] Deploy to GitHub Pages

## 💡 Pro Tips

1. **Make a backup**: Copy the original `index.html` before making changes
2. **Test locally**: Open the file in your browser to preview changes
3. **Use emoji**: Kids love emojis - add them anywhere!
4. **Keep it simple**: Don't change too much at once
5. **Mobile first**: Test on your phone to ensure it looks good

---

**Happy customizing! 🌙✨**