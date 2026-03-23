# Professional CV & Portfolio

A modern, responsive CV/portfolio website built with HTML and Tailwind CSS. Perfect for showcasing your professional work, education, skills, and projects.

## Features

✨ **Modern Design**
- Clean, professional aesthetic with a blue color theme
- Fully responsive layout (mobile, tablet, desktop)
- Smooth animations and transitions
- Glassmorphism effects in navigation

📱 **Responsive Design**
- Mobile-first approach
- Optimized for all screen sizes
- Touch-friendly navigation

🎨 **Tailwind CSS**
- Utility-first CSS framework
- No build process required (CDN included)
- Easy customization of colors and styles

📋 **Complete Sections**
- About/Hero section with your photo
- Education background
- Project showcase with descriptions
- Skills with proficiency indicators
- Footer with social links

## Project Structure

```
CV_PortfolioPersonal/
├── index.html          # Main portfolio page
├── README.md           # This file
└── .github/
    └── copilot-instructions.md
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required!

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Or use VS Code Live Server:
   - Install "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

## Customization Guide

### Update Your Information

1. **Name & Title**
   - Find "Your Name" in the HTML and replace with your actual name
   - Update "Full Stack Developer | Problem Solver" with your title

2. **Photo**
   - Replace the image URL in the hero section:
   ```html
   <img src="your-photo-url" alt="Your Name" ...>
   ```
   - Or save a local image and reference it: `src="photo.jpg"`

3. **Education**
   - Update degree name, field, university, and dates
   - Modify coursework and descriptions

4. **Projects**
   - Update project titles, descriptions, and technologies
   - Add links to your project demos and GitHub repositories
   - Replace gradient colors if desired

5. **Skills**
   - Modify skill names and proficiency percentages
   - Add or remove skills as needed

6. **Contact Links**
   - Update LinkedIn, GitHub, and email links
   - Add additional social media links if desired

7. **Colors & Styling**
   - Blue theme can be customized by modifying Tailwind color classes:
     - `from-blue-600` → different blue shade
     - `to-indigo-600` → different color
     - See [Tailwind Colors](https://tailwindcss.com/docs/customizing-colors)

### Dark Mode

To add dark mode support, add this to your body tag in HTML:
```html
<body class="... dark">
```

Then use dark: prefixes on your Tailwind classes:
```html
<div class="bg-white dark:bg-gray-900">
```

## Tailwind CSS Classes Used

- **Colors**: blue, indigo, cyan, gray
- **Spacing**: p-, m-, w-, h- utilities
- **Layout**: grid, flex, max-w utilities
- **Effects**: shadow, opacity, transition, hover
- **Responsive**: sm:, md:, lg: breakpoints

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Deploying Your Portfolio

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push the `index.html` to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be available at: `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop your folder
3. Your site will be live instantly

### Option 3: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

## Performance Tips

- Image files are optimized with CDN URLs
- Tailwind CSS is from CDN (loaded once, cached by browsers)
- Minimized CSS through utility approach
- Fast loading times on all devices

## Accessibility

- Semantic HTML structure
- ARIA labels where appropriate
- Keyboard navigation support
- High contrast colors for readability
- Alt text for images

## Future Enhancements

Consider adding:
- Testimonials section
- Blog/Articles section
- Contact form (with backend service)
- Dark mode toggle
- Age/Experience counter
- Animated charts for skills
- Case studies for projects

## License

This project is open source and available under the MIT License.

## Support

Have questions? Check:
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [MDN Web Docs](https://developer.mozilla.org/)
- [HTML & CSS Best Practices](https://www.w3schools.com/)

---

**Created with ❤️ for your professional success**

Happy coding! 🚀
