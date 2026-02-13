# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static single-page financial landing page for "Apex Capital" - an investment services company. The site is built with vanilla HTML, CSS, and JavaScript with no build tools or frameworks.

## Running the Project

Since this is a static site with no build process:

```bash
# Open in browser (macOS)
open index.html

# Or serve with any static server, e.g.:
python3 -m http.server 8000
npx serve
```

## Architecture

### File Structure

- `index.html` - Single page containing all sections (header, hero, services, about, contact, footer) and inline JavaScript for mobile navigation
- `styles.css` - All CSS styles including responsive breakpoints at 768px and 1024px
- `images/` - Static assets including logo, service icons, team photo, hero video

### Key Implementation Details

**Navigation**: Fixed header with blur backdrop. Mobile uses a slide-in drawer from the right with a mask overlay. JavaScript handles toggle state and scroll-based header styling.

**Hero Section**: Supports optional video background (`images/hero-bg.mp4`) with a blue gradient overlay. Falls back gracefully if video is absent.

**Services Grid**: Uses CSS Grid with `auto-fit` and `minmax(280px, 1fr)` for responsive columns. Cards have hover animations with a sliding top border effect.

**Responsive Breakpoints**:
- Desktop: > 768px
- Mobile: <= 768px (triggers hamburger menu, single-column layouts)
- Tablet: 769px-1024px (adjusted padding)

### Images

Service icons in `images/` are expected to be square PNGs. Required images:
- `logo.png` - Company logo
- `team.jpg` - Team photo for about section
- `hero-bg.mp4` or `hero-bg.jpg` - Hero background
- Service icons matching the names in the service cards
