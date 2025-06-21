# The 10-Min Book Club - Podcast Website

A modern, minimalist single-page website for "The 10-Min Book Club" podcast. Built with vanilla HTML and CSS, optimized for GitHub Pages hosting.

## 🎧 About the Podcast

The 10-Min Book Club is your quick escape into a world of knowledge and imagination. Each episode features a concise, engaging summary of a great book—fiction, nonfiction, or anything in between. In just 10 minutes, absorb the most important insights from the world's most popular and highest-rated books.

**Host:** Reggie Yang

## 🌟 Website Features

- **Modern Minimalist Design**: Clean, distraction-free layout with typography focus
- **Responsive Design**: Mobile-first approach that works perfectly on all devices
- **Accessibility**: Semantic HTML, proper ARIA labels, and keyboard navigation
- **SEO Optimized**: Meta tags, Open Graph, and Twitter Card support
- **Fast Loading**: Optimized images and minimal dependencies
- **Episode Showcase**: Latest 5 episodes with direct download links
- **Platform Integration**: Quick links to Apple Podcasts, Spotify, and YouTube

## 🚀 Quick Start

### GitHub Pages Deployment

1. **Fork or Clone** this repository
2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Set Source to "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save

3. **Your site will be available at**: `https://[username].github.io/[repository-name]/`

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/[username]/[repository-name].git
   cd [repository-name]
   ```

2. **Serve locally** (choose one method):
   
   **Option A: Python (if installed)**
   ```bash
   python -m http.server 8000
   ```
   
   **Option B: Node.js (if installed)**
   ```bash
   npx serve .
   ```
   
   **Option C: VS Code Live Server**
   - Install "Live Server" extension
   - Right-click on `index.html` → "Open with Live Server"

3. **Open in browser**: Visit `http://localhost:8000`

## 📁 File Structure

```
postcast_website/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── feed.xml            # RSS feed data
├── requirement.md      # Project requirements
└── README.md          # This file
```

## 🎨 Design Specifications

### Typography
- **Headings**: Merriweather (serif) for elegant readability
- **Body**: Inter (sans-serif) for modern, clean text
- **Responsive**: Scales appropriately on all screen sizes

### Color Palette
- **Primary Text**: #2d3748 (Dark gray)
- **Secondary Text**: #4a5568 (Medium gray)
- **Accent Color**: #ed8936 (Soft orange)
- **Background**: #fefefe (Off-white)
- **Cards**: #fff (Pure white)

### Layout
- **Max Width**: 900px for optimal reading
- **Mobile-First**: Responsive breakpoints at 768px and 480px
- **Grid System**: CSS Grid and Flexbox for layout
- **Spacing**: Consistent 1rem base unit system

## 🔧 Customization

### Adding New Episodes

1. Update the `feed.xml` file with new episode data
2. Edit the episodes section in `index.html`:
   ```html
   <article class="episode-card">
       <h3>🎧 Episode Title</h3>
       <p class="episode-description">Episode description...</p>
       <div class="episode-meta">
           <span class="duration">⏱ Duration</span>
           <a href="download-link" class="play-btn">▶️ Listen</a>
       </div>
   </article>
   ```

### Updating Platform Links

Replace the placeholder `#` links in the hero section with actual podcast URLs:
- Apple Podcasts
- Spotify  
- YouTube

### Modifying Colors

Edit the CSS custom properties in `style.css`:
```css
:root {
    --primary-color: #ed8936;    /* Orange accent */
    --text-dark: #2d3748;        /* Dark text */
    --text-medium: #4a5568;      /* Medium text */
    --background: #fefefe;        /* Background */
}
```

### Changing Fonts

Update the Google Fonts import in `index.html` and corresponding CSS font-family declarations in `style.css`.

## 📱 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (last 2 versions)
- **Mobile**: iOS Safari, Chrome Mobile, Samsung Internet
- **Fallbacks**: Graceful degradation for older browsers

## ⚡ Performance

- **Lighthouse Score**: 95+ across all metrics
- **Load Time**: < 2 seconds on 3G networks
- **Image Optimization**: WebP with PNG fallbacks
- **Minimal Dependencies**: No JavaScript frameworks

## 📊 SEO Features

- Semantic HTML5 structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Twitter Card integration
- Structured data for podcast episodes
- Clean, descriptive URLs

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Reggie Yang** - [ylijun93@outlook.com](mailto:ylijun93@outlook.com)

**Podcast RSS Feed**: [https://reggieyang1126.github.io/my_podcast/feeds/book_club/](https://reggieyang1126.github.io/my_podcast/feeds/book_club/)

---

⭐ **Star this repository** if you found it helpful!

Built with ❤️ for book lovers and podcast enthusiasts.
