# Apex Capital - Financial Landing Page

A modern, responsive landing page for Apex Capital - a professional investment services company.

## Features

- **Dark/Light Theme Toggle** - Smooth theme switching with persistent user preference
- **Responsive Design** - Optimized for mobile, tablet, and desktop
- **Smooth Animations** - Fade-in effects, hover animations, ripple button effects
- **Interactive Calculator** - Investment growth calculator with real-time results
- **Contact Form** - Clean, accessible contact form with validation
- **Social Proof Toast** - Dynamic notification system showing user activity
- **SEO Optimized** - Meta tags, Open Graph, Twitter Cards, sitemap, robots.txt
- **Accessible** - Skip navigation, ARIA labels, focus states

## Tech Stack

- Pure HTML, CSS, and JavaScript
- No frameworks or build tools required

## Getting Started

### Open in Browser

Simply open `index.html` in your browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Or use a local server
python3 -m http.server 8000
npx serve
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
FinancialLandingPage/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── images/             # Static images and icons
├── robots.txt         # SEO robots file
├── sitemap.xml        # SEO sitemap
└── CLAUDE.md          # Project instructions for AI
```

## Customization

### Colors

Main colors are defined in `styles.css`:
- Primary accent: `#2563eb` (blue)
- Backgrounds: White/Light gray (light mode), Dark slate (dark mode)

### Dark Mode

The theme automatically detects user preference and stores the selection in localStorage. Toggle button is available in the navigation.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Private - All rights reserved
