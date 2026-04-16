# Technical Writer Portfolio Website

A professional, responsive portfolio website designed specifically for technical writers to showcase their documentation, guides, API docs, and specifications.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Multi-page Site**: Home, Portfolio, About, and Contact pages
- **Portfolio Filtering**: Filter work by category (API Docs, Guides, Specifications)
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: Scroll animations and transitions
- **Modern Styling**: Clean, professional design with smooth interactions

## Project Structure

```
portfolio/
├── index.html          # Home page
├── portfolio.html      # Portfolio/work showcase
├── about.html          # About the writer
├── contact.html        # Contact form
├── css/
│   └── style.css       # All styles
├── js/
│   └── script.js       # JavaScript functionality
├── assets/             # Place images/files here
└── README.md          # This file
```

## Pages

### Home (index.html)
- Hero section with call-to-action
- Featured expertise highlights
- Introduction to services

### Portfolio (portfolio.html)
- Showcase of technical writing samples
- Filterable by category: API Docs, Guides, Specifications
- Portfolio items with descriptions and links

### About (about.html)
- Writer biography and background
- Professional highlights
- Areas of expertise

### Contact (contact.html)
- Contact information
- Contact form with validation
- Links to social media

## Customization Guide

### Update Writer Information

1. **Home Page** (`index.html`):
   - Change the hero title and subtitle
   - Update featured expertise sections

2. **About Page** (`about.html`):
   - Update the background story in the "My Background" section
   - Modify highlights list with actual achievements
   - Update expertise sections with specific skills

3. **Portfolio Page** (`portfolio.html`):
   - Replace portfolio items with actual work samples
   - Update categories, titles, descriptions, and links
   - Add/remove portfolio items as needed

4. **Contact Page** (`contact.html`):
   - Replace email, phone, and social media links
   - Update inquiry types if needed
   - Note: Form submission currently shows a message but doesn't send data

### Colors and Styling

Edit the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue */
    --secondary-color: #1e40af;    /* Darker blue */
    --accent-color: #0ea5e9;       /* Light blue */
    --text-dark: #1f2937;          /* Dark gray */
    --text-light: #6b7280;         /* Light gray */
    --bg-light: #f9fafb;           /* Light background */
}
```

### Add Images

1. Create an `images/` folder in the `assets/` directory
2. Add your portfolio images/screenshots
3. Update portfolio items to include images (you can add `<img>` tags)

### Contact Form Setup

To make the contact form functional:

1. **Option 1 - Email Service**: Use a service like FormSubmit.co, Basin, or Formspree
2. **Option 2 - Backend**: Set up a backend endpoint to handle form submissions
3. Update the form action or add an API call in `js/script.js`

Example with FormSubmit.co:
```html
<form class="contact-form" action="https://formsubmit.co/your-email@example.com" method="POST">
    <!-- form fields -->
</form>
```

## Features in Detail

### Navigation
- Sticky header that stays at top while scrolling
- Active page indicator with underline
- Mobile hamburger menu that animates

### Portfolio Filtering
- Click filter buttons to show/hide categories
- "All" button shows everything
- Categories: API Docs, Guides, Specifications

### Responsive Design
- Desktop: Multi-column layouts
- Tablet: Adjusted spacing and column counts
- Mobile: Single-column layout with touch-friendly elements

### Accessibility
- Semantic HTML structure
- Clear visual hierarchy
- Readable font sizes and colors
- Good contrast ratios

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Getting Started

1. Open `index.html` in your web browser to preview
2. Customize all content in the HTML files
3. Update styling in `css/style.css` as needed
4. Test on mobile devices to ensure responsiveness
5. Deploy to hosting service (GitHub Pages, Netlify, Vercel, etc.)

## Deployment Options

### GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Choose the `main` branch as source
4. Site will be available at `https://username.github.io/portfolio`

### Netlify
1. Connect your GitHub repository
2. Build settings: Leave as default (no build process needed)
3. Deploy

### Vercel
1. Connect your GitHub repository
2. Deploy

## Tips for Technical Writers

1. **Portfolio Items**: 
   - Link to actual documentation or samples
   - Include specific technologies/tools used
   - Highlight the impact or value of your work

2. **About Section**:
   - Mention specific industries or platforms you've worked with
   - Include any certifications or notable achievements
   - Highlight your unique perspective on documentation

3. **Contact Form**:
   - Clearly state response time expectations
   - List different inquiry types (Full-time, Contract, Consulting, etc.)
   - Make it easy for potential clients to reach you

## License

Free to use and customize for your professional portfolio.

## Support

For questions or issues, refer to the code comments or standard web development resources.
