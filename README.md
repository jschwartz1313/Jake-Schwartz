# Jake Schwartz - Personal Website

A responsive personal website showcasing my background in quantitative energy analysis, geospatial application development, and data systems.

## Overview

This website serves as my professional online presence, highlighting my education, technical skills, work experience, and interests across energy, geospatial analytics, and software development.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, minimalist design with smooth animations and transitions
- **Professional Sections**:
  - Hero section with call-to-action
  - About section with core competencies
  - Education and work experience
  - Career interests showcase
  - Contact section with GitHub, LinkedIn, email, and resume download
- **Smooth Navigation**: Animated scrolling between sections
- **Performance Optimized**: Fast loading with vanilla JavaScript (no frameworks)

## Structure

```
Jake-Schwartz/
├── index.html              # Main website file
├── Jake-Schwartz-Resume-Energy-Analyst.pdf     # Downloadable energy resume
├── Jake-Schwartz-Resume.pdf                    # Generic resume filename for compatibility
└── README.md              # This file
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/jschwartz1313/Jake-Schwartz.git
   cd Jake-Schwartz
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # or
     npx serve
     ```

3. Navigate to `http://localhost:8000` in your browser

### Deployment

This site can be easily deployed using:

- **GitHub Pages**:
  1. Go to repository Settings > Pages
  2. Select main branch as source
  3. The site will be live at `https://jschwartz1313.github.io/Jake-Schwartz/`

## Customization

To personalize the website for your needs:

1. **Update Contact Information** (in `index.html`):
   - Replace email address in the contact section
   - Update LinkedIn profile URL
   - Ensure resume PDF filename matches your file

2. **Modify Content**:
   - Edit the about section text to reflect your background
   - Update core competencies list with your skills
   - Customize career interests cards with your focus areas

3. **Adjust Colors** (CSS variables in `<style>` section):
   ```css
   --primary-color: #2c3e50;
   --accent-color: #3498db;
   ```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Vanilla JS for smooth interactions
- **No Dependencies**: Pure frontend code, no build process required

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Contact

For inquiries or opportunities, please reach out through the contact section on the website.

---

Built with HTML, CSS, and JavaScript.
