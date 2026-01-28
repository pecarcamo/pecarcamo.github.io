# Pablo Cárcamo - Personal Academic Website

A clean, responsive personal academic website built with plain HTML, CSS, and JavaScript.

## Features

- **Bilingual**: English and Spanish versions
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern Styling**: Deep forest + high desert color palette with elegant typography
- **Easter Egg**: Hidden bird element on every page (click to discover!)
- **No Framework**: Pure HTML/CSS/JS for easy maintenance and fast loading

## Structure

```
website/
├── index.html              # English homepage
├── index-es.html           # Spanish homepage
├── research.html           # Research interests and projects
├── publications.html       # Academic publications
├── projects.html          # Creative and consulting projects
├── cv.html                # Curriculum vitae
├── style.css              # All styles
├── README.md              # This file
└── assets/
    ├── headshot.jpg       # Profile photo (220x220px recommended)
    └── CV_Pablo_Carcamo.pdf  # PDF version of CV
```

## Setup

### Required Assets

Before deploying, you need to add:

1. **Profile Photo**: Add `headshot.jpg` to the `assets/` folder
   - Recommended size: 220x220px
   - Should be a square photo with your face clearly visible

2. **CV PDF**: Add `CV_Pablo_Carcamo.pdf` to the `assets/` folder
   - This will be linked from the CV page for download

### Placeholder Links to Update

There's one placeholder link that needs to be updated:

- **Consultancy Link**: Search for `id="consultancy-link"` in `index.html` and `index-es.html`
  - Currently set to `href="#"`
  - Update with the actual consultancy website URL when available

## Deployment

This website is ready to deploy to any static hosting service:

### GitHub Pages
1. Create a GitHub repository
2. Push all files to the repository
3. Go to Settings > Pages
4. Select your branch and root folder
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the entire folder to Netlify
2. Or connect to a GitHub repository for automatic deployments
3. Your site will be live immediately

### Custom Domain
Both GitHub Pages and Netlify support custom domains. Follow their documentation to connect your own domain.

## Customization

### Colors
All colors are defined as CSS variables in `style.css`. Look for the `:root` section at the top to modify the color palette.

### Fonts
The site uses Google Fonts:
- **Headings**: Fraunces (serif)
- **Body**: Source Sans 3 (sans-serif)

To change fonts, update the `@import` statement in `style.css` and modify the `font-family` declarations.

### Content
All content is in plain HTML, so you can edit it directly in the HTML files. Each page is self-contained for easy maintenance.

## Easter Egg

There's a hidden bird icon in the bottom-right corner of every page that becomes visible after scrolling or after 5 seconds. Clicking it reveals a personal message and triggers a fun animation. The JavaScript code is included at the bottom of each HTML file.

## Browser Support

This website works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

This is a personal website. Feel free to use the design as inspiration for your own site, but please don't copy the content directly.

## Contact

For questions or issues with the website, contact:
- Email: pabloc@vt.edu
- LinkedIn: https://www.linkedin.com/in/pablo-carcamo-corral-00273a21/
