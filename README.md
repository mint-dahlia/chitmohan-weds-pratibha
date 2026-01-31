# ChitMohan 💕 Pratibha - Wedding Website

A beautiful wedding invitation website celebrating the union of ChitMohan and Pratibha (Tanisha) on **10 February 2026** at Jodhpur, Rajasthan.

## 🌐 Live Website

Visit: [https://yourusername.github.io/chitmohan-weds-pratibha](https://yourusername.github.io/chitmohan-weds-pratibha)

## ✨ Features

- **Vibrant Rajasthani Design** - Traditional colors (maroon, gold, orange) with modern styling
- **Countdown Timer** - Live countdown to the wedding day
- **Responsive Design** - Works beautifully on mobile, tablet, and desktop
- **Smooth Animations** - Reveal-on-scroll effects and floating decorations
- **Photo Gallery** - Grid layout with lightbox view
- **Background Music** - Optional music toggle button
- **Hindi Typography** - Beautiful Devanagari fonts for Hindi text
- **Click-to-Call** - Easy contact buttons

## 📁 Project Structure

```
chitmohan-weds-pratibha/
├── index.html          # Complete website (HTML + CSS + JS)
├── assets/
│   ├── music.mp3       # Add your background music here
│   └── gallery/        # Add wedding photos here
│       ├── photo1.jpg
│       ├── photo2.jpg
│       └── ...
├── README.md           # This file
└── LICENSE
```

## 🎵 Adding Background Music

1. Find a royalty-free wedding music track (MP3 format)
2. Rename it to `music.mp3`
3. Place it in the `assets/` folder
4. The music button will now work!

**Recommended sources for free music:**
- [Pixabay Music](https://pixabay.com/music/)
- [Free Music Archive](https://freemusicarchive.org/)
- [Mixkit](https://mixkit.co/free-stock-music/)

## 📷 Adding Photos to Gallery

1. Prepare your photos (recommended: square or 4:3 aspect ratio)
2. Optimize them for web (max 1200px width, JPEG quality 80%)
3. Place them in `assets/gallery/` folder
4. Update the gallery section in `index.html`:

```html
<!-- Replace placeholder divs with actual images -->
<div class="gallery-item aspect-square rounded-xl overflow-hidden cursor-pointer hover:scale-105 transition-transform duration-300 shadow-lg">
  <img src="assets/gallery/photo1.jpg" alt="Photo description" class="w-full h-full object-cover">
</div>
```

## 🗺️ Adding Google Maps

To embed the venue map, replace the map placeholder in the Venue section:

```html
<!-- Replace this div with Google Maps embed -->
<iframe 
  src="https://www.google.com/maps/embed?pb=YOUR_EMBED_CODE"
  width="100%" 
  height="320" 
  style="border:0;" 
  allowfullscreen="" 
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade">
</iframe>
```

**To get embed code:**
1. Go to [Google Maps](https://maps.google.com)
2. Search for your venue
3. Click Share → Embed a map
4. Copy the iframe code

## 🎨 Customization

### Colors
The color palette is defined in the Tailwind config. To change colors, modify the `tailwind.config` section in `index.html`:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        maroon: { /* your colors */ },
        gold: { /* your colors */ },
        // ...
      }
    }
  }
}
```

### Fonts
Currently using:
- **Playfair Display** - Headings
- **Poppins** - Body text
- **Noto Sans Devanagari** - Hindi text

Change fonts by updating the Google Fonts link and `fontFamily` config.

## 🚀 Deployment

The website is already configured for GitHub Pages:

1. Push your changes to the `main` branch
2. Go to Repository Settings → Pages
3. Select Source: "Deploy from a branch"
4. Select Branch: `main` / `root`
5. Save and wait for deployment

Your site will be live at `https://yourusername.github.io/chitmohan-weds-pratibha`

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome for Android)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ for ChitMohan & Pratibha's special day
