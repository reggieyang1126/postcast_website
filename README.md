# The 10-Min Book Club

A modern, minimalist podcast website featuring book summaries in bite-sized episodes. Built for GitHub Pages with vanilla HTML and CSS.

## About

Quick, insightful book summaries in just 10 minutes. Get the best insights from bestselling books — all in under 10 minutes.

**Host:** Reggie Yang

## Features

- 🎨 Clean, responsive design
- 🎵 Built-in audio player
- 📱 Mobile-friendly
- ⚡ Fast loading
- 🚀 GitHub Pages ready

## Quick Deploy

1. **Fork** this repository
2. **Enable GitHub Pages** in Settings → Pages → Deploy from main branch
3. **Visit** your site at `https://[username].github.io/[repository-name]/`

## Local Development

```bash
# Clone and serve
git clone [repository-url]
cd postcast_website
python -m http.server 8000
```

Visit `http://localhost:8000`

## File Structure

```
postcast_website/
├── index.html     # Main page
├── style.css      # Styling
├── feed.xml       # RSS feed
├── img/           # Images
└── audio/         # Audio files
```

## Adding Episodes

1. **Add audio file** to `audio/` folder
2. **Update** `index.html` episodes section:
   ```html
   <article class="episode-card">
       <h3>🎧 Book Title</h3>
       <p class="episode-description">Description...</p>
       <div class="episode-meta">
           <span class="duration">⏱ 10:30</span>
           <div class="custom-audio-player" data-src="audio/filename.mp3">
               <!-- Audio player code -->
           </div>
       </div>
   </article>
   ```

## Contact

**Reggie Yang** - ylijun93@outlook.com

---

Built with ❤️ for book lovers and podcast enthusiasts.
