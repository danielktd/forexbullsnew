# Forex Bulls Academy

A modern, responsive website for Forex Bulls Academy - a premier forex trading education platform featuring expert mentors and comprehensive trading courses.

## 🌐 Live Site

[forexbullslive.com](https://forexbullslive.com)

## 📋 Project Overview

Forex Bulls Academy is an educational platform dedicated to teaching forex trading strategies and techniques. The website showcases:

- **Expert Mentors** - Meet the team of experienced forex trading professionals
- **Trading Insights** - Educational content and market analysis
- **Community** - Connect with fellow traders and mentors
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Webflow (custom components)
- **Styling**: TailwindCSS-inspired custom CSS with CSS variables
- **Images**: Cloudinary CDN for optimized image delivery
- **Hosting**: Netlify with automatic deployments

## 📁 Project Structure

```
PLP.io/
├── index.html              # Main landing page
├── css/
│   ├── main.css           # Primary stylesheet with Webflow components
│   └── style.css          # Custom animations and overrides
├── images/                # Local image assets
├── favicon.png            # Site favicon
└── README.md              # This file
```

## 🎨 Key Features

### Responsive Design
- Mobile-first approach
- Breakpoints for tablet and desktop views
- Optimized images with srcset for different screen sizes

### Performance Optimizations
- Lazy loading on all images
- Cloudinary CDN for fast image delivery with auto-optimization (f_auto, q_auto)
- CSS variables for efficient theming
- Aspect ratio declarations to prevent layout shift

### Animations & Interactions
- Smooth hover effects with ease-in-out transitions
- Fade and scale animations on page load
- Gradient overlays on team member cards
- Interactive state cards with smooth color transitions

### Accessibility
- Semantic HTML structure
- Alt text on all images
- Proper heading hierarchy
- ARIA labels where needed

## 🚀 Getting Started

### Prerequisites
- Node.js (for local development if needed)
- Git for version control

### Installation

1. Clone the repository:
```bash
git clone git@github.com:danielktd/forexbullsnew.git
cd forexbullsnew
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## 📝 Content Sections

### Hero Section
- Eye-catching banner with call-to-action
- Featured images with gradient overlays
- Responsive layout that adapts to screen size

### Team Section
- Showcase of mentors with full-size images
- Social media links (Instagram, TikTok)
- Professional titles and roles

### Footer
- Social media links (Telegram, Facebook, WhatsApp, YouTube)
- Responsive layout with desktop/mobile variants
- Centered logo with gradient overlay

## 🎯 CSS Architecture

### Color System
Uses CSS variables for consistent theming:
- Primary colors: `--_color---used--primary-color`
- Secondary colors: `--_color---used--secondary-color-1`
- Background: `--_color---used--bg-colour`
- Borders: `--_color---used--border-color-1`

### Typography
- Font Family: Geist (400, 500, 600, 700, 800 weights)
- Responsive font sizes using CSS variables
- Consistent line heights for readability

### Spacing & Layout
- Grid-based layout system
- Consistent gap variables (gap-12, gap-16, gap-24, etc.)
- Flexbox for component alignment
- CSS Grid for complex layouts

## 🖼️ Image Management

All images are hosted on Cloudinary with automatic optimization:
- Format auto-selection (WebP, JPEG, PNG)
- Quality auto-adjustment
- Responsive sizing with srcset
- Lazy loading for performance

Example image URL structure:
```
https://res.cloudinary.com/tech-hub-hosting/image/upload/f_auto,q_auto,w_auto/v{timestamp}/{image-name}.{ext}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 767px
- **Tablet**: 768px - 991px
- **Desktop**: > 992px

## 🔄 Deployment

### Netlify Deployment

1. Connect your GitHub repository to Netlify
2. Set build settings (if needed):
   - Build command: (leave empty for static site)
   - Publish directory: `/` (root)

3. Deploy automatically on push to main branch

### Environment Variables
No environment variables required for this static site.

## 🐛 Known Issues & Improvements

- Team member images now display full height with `object-fit: contain`
- YouTube embeds use privacy-enhanced mode (youtube-nocookie.com)
- Social links have responsive variants for mobile/desktop

## 📞 Contact & Support

For questions or support regarding the website:
- Email: [contact information]
- Instagram: [@forexbulls](https://instagram.com/forexbulls)
- TikTok: [@forexbulls.01](https://tiktok.com/@forexbulls.01)

## 📄 License

This project is proprietary to Forex Bulls Academy. All rights reserved.

## 🤝 Contributing

For team members contributing to this project:

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Commit changes: `git commit -m 'Add your feature'`
3. Push to branch: `git push origin feature/your-feature`
4. Open a Pull Request

## 📚 Resources

- [Webflow Documentation](https://webflow.com/help)
- [Cloudinary Image Optimization](https://cloudinary.com/documentation)
- [CSS Variables Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- [Responsive Design Best Practices](https://web.dev/responsive-web-design-basics/)

---

**Last Updated**: February 2026  
**Version**: 1.0.0
