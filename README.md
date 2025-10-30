# Minimalist Portfolio

A clean, modern personal portfolio website built with pure HTML, CSS, and JavaScript. Features a minimalist design aesthetic with smooth animations and responsive layout.

## Features

- **Minimalist Design**: Clean, uncluttered interface with focus on content
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle fade-in effects and scroll-based animations
- **Interactive Elements**: Custom cursor effect, card tilt on hover, typing animation
- **Modern Navigation**: Fixed navbar with smooth scrolling and active section highlighting
- **Mobile Menu**: Hamburger menu for mobile devices
- **Performance Optimized**: Lazy loading support and efficient CSS transitions
- **Accessibility**: Semantic HTML and keyboard-friendly navigation

## Sections

1. **Hero** - Introduction with name and tagline
2. **About** - Brief personal introduction
3. **Projects** - Showcase of selected work with descriptions and tech stack
4. **Skills** - List of technical skills organized by category
5. **Contact** - Contact information and social links

## Customization

### Update Personal Information

Edit `index.html` to customize:

- Your name in the hero section
- About section text
- Project details (titles, descriptions, tags, links)
- Skills lists
- Contact information (email, GitHub, LinkedIn, Twitter)
- Footer copyright

### Color Scheme

Modify CSS variables in `styles.css` (lines 11-18):

```css
:root {
    --color-bg: #ffffff;        /* Background color */
    --color-text: #1a1a1a;      /* Primary text color */
    --color-text-light: #666666; /* Secondary text color */
    --color-accent: #000000;     /* Accent color */
    --color-border: #e5e5e5;     /* Border color */
    --color-hover: #333333;      /* Hover state color */
    --color-alt-bg: #fafafa;     /* Alternate background */
}
```

### Typography

Change fonts in `styles.css` (lines 26-27):

```css
--font-primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', sans-serif;
--font-mono: 'SF Mono', 'Monaco', 'Inconsolata', 'Courier New', monospace;
```

### Spacing

Adjust spacing values in `styles.css` (lines 20-24):

```css
--spacing-xs: 0.5rem;
--spacing-sm: 1rem;
--spacing-md: 2rem;
--spacing-lg: 4rem;
--spacing-xl: 6rem;
```

## JavaScript Features

### Smooth Scrolling
Navigation links smoothly scroll to their target sections.

### Active Link Highlighting
Navigation links highlight based on the current scroll position.

### Intersection Observer
Sections and cards animate in when scrolled into view.

### Navbar Behavior
- Adds shadow when scrolled
- Hides on scroll down, shows on scroll up (on mobile)

### Card Tilt Effect
Project cards tilt subtly on mouse movement for a 3D effect.

### Typing Effect
Hero subtitle types out on page load.

### Custom Cursor
Interactive cursor that changes on hover (desktop only).

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser
3. Customize the content to match your information
4. Deploy to your hosting platform of choice

## Deployment

This is a static website and can be deployed to:

- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Import the project from Git
- **Cloudflare Pages**: Connect your Git repository
- **Any static hosting service**

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles and responsive design
├── script.js       # Interactive functionality
└── README.md       # Documentation
```

## Performance Tips

1. Add images in WebP format for better compression
2. Lazy load images using `loading="lazy"` attribute
3. Minify CSS and JavaScript for production
4. Enable gzip compression on your server
5. Use a CDN for faster asset delivery

## Accessibility

- Semantic HTML5 elements
- ARIA labels where appropriate
- Keyboard navigation support
- Focus indicators on interactive elements
- Sufficient color contrast ratios
- Responsive text sizing

## License

Free to use for personal and commercial projects.

## Credits

Created with Claude Code
Design inspired by minimalist principles and modern web trends

---

**Made with code and care**
