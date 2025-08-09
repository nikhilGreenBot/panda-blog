Hi I am nikhilGreenBot — I like cats, ramen, and photography in no particular order. Work in progress.

## Features

- ✨ Clean, minimal design
- 📱 Responsive layout
- 🌙 Dark mode support
- ⚡ Fast loading
- 📝 Easy to customize
- 🚀 Ready for GitHub Pages hosting

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing the content!

### Customization

#### Content
- Edit `index.html` to change your blog posts
- Update the navigation links
- Modify the hero section with your name and tagline

#### Styling
- Edit `styles.css` to change colors, fonts, and layout
- The design uses the Inter font family
- Supports both light and dark modes

#### Functionality
- Edit `script.js` to add new interactive features
- Currently includes smooth scrolling and animations

## Hosting on GitHub Pages

1. **Create a GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/panda-blog.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll down to "GitHub Pages"
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"

3. **Your blog will be available at:**
   `https://yourusername.github.io/panda-blog`

## File Structure

```
panda-blog/
├── index.html          # Main blog page
├── styles.css          # Styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Adding New Posts

To add a new blog post, edit the `index.html` file and add a new `<article>` element in the `.posts` section:

```html
<article class="post">
    <h2><a href="#your-post-title">Your Post Title</a></h2>
    <div class="post-meta">
        <time datetime="2025-01-20">20 Jan 2025</time>
    </div>
    <p>Your post content goes here...</p>
    <div class="post-footer">
        <a href="#your-post-title" class="read-more">Read more →</a>
    </div>
</article>
```

## Customization Tips

### Colors
The main colors used are:
- Primary text: `#333` (light mode) / `#e5e5e5` (dark mode)
- Secondary text: `#666` (light mode) / `#999` (dark mode)
- Borders: `#e5e5e5` (light mode) / `#333` (dark mode)

### Fonts
The blog uses the Inter font family. You can change this in `styles.css` by modifying the `font-family` property in the `body` selector.

### Layout
The maximum width is set to 800px for optimal reading experience. You can adjust this in the `.container` class.

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ by Panda 