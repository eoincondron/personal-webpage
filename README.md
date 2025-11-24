# Personal Webpage

A professional landing page showcasing projects, experience, and links to social profiles.

## Structure

```
personal-webpage/
├── index.html          # Main HTML file
├── styles/
│   └── main.css       # CSS styles
├── assets/
│   └── images/        # Images and icons
├── scripts/
│   └── main.js        # JavaScript (optional)
└── README.md          # This file
```

## Getting Started

1. Update `index.html` with your personal information
2. Customize colors in `styles/main.css` (see CSS variables in `:root`)
3. Add your project cards in the projects section
4. Update social links with your actual profiles
5. Add any images to `assets/images/`

## Hosting Options

- **GitHub Pages**: Free hosting directly from your repository
- **Netlify**: Drag-and-drop deployment with continuous integration
- **Vercel**: Simple deployment with great performance
- **Cloudflare Pages**: Fast global CDN with free tier

## Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with npx)
npx serve
```

Then visit `http://localhost:8000`

## Customization Tips

- Replace placeholder text with your information
- Add a profile photo in the hero section
- Include screenshots for your projects
- Consider adding a dark mode toggle
- Add animations or transitions for polish
