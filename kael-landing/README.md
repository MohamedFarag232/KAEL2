# KAEL - Performance Marketing Agency Landing Page

A premium, elegant, and minimalist landing page for KAEL performance marketing agency. Built with pure HTML, CSS, and vanilla JavaScript - no frameworks required.

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript (ES6)** - Interactive functionality
- **AOS** - Scroll animations
- **Lucide Icons** - Icon library
- **Google Fonts (Inter)** - Typography

## Features

- ✅ Modern dark theme design
- ✅ Premium and elegant aesthetic
- ✅ Fully responsive (Desktop, Tablet, Mobile)
- ✅ Smooth scroll animations (AOS)
- ✅ Sticky navigation with scroll effect
- ✅ Mobile menu with smooth toggle
- ✅ Animated counters for results
- ✅ FAQ accordion
- ✅ Scroll progress indicator
- ✅ Back to top button
- ✅ Active navigation highlighting
- ✅ SEO optimizedmeta tags, semantic HTML)
- ✅ Accessible (ARIA labels, semantic structure)
- ✅ Fast loading (no build process required)

## Project Structure

```
kael-landing/
│── index.html
│── css/
│     style.css
│     responsive.css
│── js/
│     main.js
│── assets/
│     images/
│     icons/
│── README.md
```

## Sections

1. **Sticky Navbar** - Logo, navigation links, CTA buttons, mobile menu
2. **Hero** - Headline, subheadline, CTAs, animated dashboard mockup
3. **Problems** - 4 cards highlighting common pain points
4. **Why KAEL** - 4 feature cards with icons
5. **Services** - 5 service cards with hover effects
6. **Process** - 5-step timeline
7. **Results** - Animated counters (+250%, -35%, 4.8x)
8. **Testimonials** - 3 client testimonials with ratings
9. **FAQ** - Accordion with 5 questions
10. **Final CTA** - Large call-to-action section
11. **Footer** - Navigation, contact info, social links

## Color Palette

- **Primary:** #2563EB
- **Background:** #0F172A
- **Cards:** #1E293B
- **Text:** #F8FAFC
- **Secondary Text:** #CBD5E1
- **Borders:** rgba(255,255,255,.08)

## How to Use

### Option 1: Direct File Opening

Simply open `index.html` in your web browser. No server or build process required.

### Option 2: Local Server (Recommended for Development)

Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js (http-server):
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

### Option 3: VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Deployment

### Netlify (Recommended) - Drag and Drop

1. Go to [netlify.com](https://netlify.com)
2. Sign up or log in
3. Drag and drop the `kael-landing` folder into the deploy area
4. That's it! Your site is live.

### Vercel

1. Push the project to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import the repository
4. Deploy automatically

### GitHub Pages

1. Push the project to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Deploy automatically

## Customization

### Changing Colors

Edit the CSS variables in `css/style.css`:

```css
:root {
    --primary: #2563EB;
    --background: #0F172A;
    --card: #1E293B;
    --text: #F8FAFC;
    --text-secondary: #CBD5E1;
    --border: rgba(255, 255, 255, 0.08);
}
```

### Changing Content

All content is in `index.html`. Edit the text, metrics, and testimonials as needed.

## License

MIT License - Feel free to use for personal or commercial projects.
