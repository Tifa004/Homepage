# 🚀 Portfolio Website - Mostafa Sakr

A modern, responsive portfolio website showcasing web development projects with a sleek design and smooth user experience.

## 🌟 Live Demo

[View Live Portfolio](https://tifa004.github.io/Homepage/)


### Desktop View
- Clean, professional layout with side-by-side hero section
- Custom skewed background design
- Project grid showcasing featured work

### Mobile View  
- Fully responsive design with optimized mobile layout
- Touch-friendly navigation and interactions
- Adaptive image sizing and content flow

## 🎨 Features

### 🖼️ Hero Section
- **Dynamic Background**: Custom CSS skewed background with gradient
- **Profile Integration**: Floating profile image with overlay text positioning
- **Responsive Text Wrapping**: Text flows naturally around images on different screen sizes
- **Social Media Links**: Direct links to GitHub, LinkedIn, and Twitter profiles

### 📱 Responsive Design
- **Fluid Layouts**: Seamless transitions between desktop, tablet, and mobile views
- **Breakpoint Strategy**: 
  - Desktop (>1200px): Full grid layout
  - Tablet (600px-1200px): Side-by-side content with natural text wrapping
  - Mobile (<600px): Stacked column layout with optimized spacing
- **Adaptive Images**: Images resize and reposition based on screen size
- **Touch Optimized**: Mobile-friendly interactions and navigation

### 🎯 Project Showcase
- **Interactive Grid**: 3-column desktop grid transitioning to responsive layouts
- **Project Cards**: Clean card design with hover effects and shadows
- **Live Demos**: Direct links to hosted projects and source code
- **Technology Tags**: Visual indicators of technologies used

### 🎭 Advanced CSS Techniques
- **Flexbox Mastery**: Complex layouts using flexbox for alignment and distribution
- **CSS Grid**: Project showcase using CSS Grid for responsive layouts
- **Custom Animations**: Smooth transitions and hover effects
- **CSS Variables**: Consistent color scheme and spacing throughout
- **Media Queries**: Comprehensive responsive design implementation

### 🌐 Footer Design
- **Contact Integration**: Professional contact information display
- **Visual Appeal**: Large background image with proper mobile optimization
- **Edge-to-Edge Images**: Full-width images touching all container edges on mobile
- **Social Links**: Consistent branding across all platforms

## 🛠️ Technologies Used

### Frontend Technologies
- **HTML5**: Semantic markup with proper structure
- **CSS3**: Advanced styling with modern features
  - Flexbox & CSS Grid
  - Custom Properties (CSS Variables)
  - Media Queries for responsive design
  - Transform & Positioning techniques
  - Box-shadow and visual effects

### Design & UX
- **Typography**: Google Fonts (Playfair Display, Roboto)
- **Color Scheme**: Professional blue theme (#004ea8)
- **Responsive Images**: Optimized for different screen sizes
- **Accessibility**: Proper contrast ratios and semantic HTML

### Development Tools
- **Git**: Version control and collaboration
- **GitHub Pages**: Free hosting for static websites
- **VS Code**: Development environment
- **Browser DevTools**: Testing and debugging

## 📁 Project Structure

```
Homepage/
├── src/
│   ├── index.html          # Main HTML structure
│   ├── styles.css          # Complete CSS styling
│   ├── script.js           # JavaScript functionality
│   └── assets/
│       ├── falcon.avif     # Profile image
│       ├── thor-ragnarok.webp # Footer background
│       └── project-images/ # Project screenshots
├── package.json            # Project dependencies
├── webpack.config.js       # Build configuration
└── README.md              # Project documentation
```

## 🎨 CSS Architecture

### Layout Strategy
- **Mobile-First Approach**: Base styles for mobile, enhanced for larger screens
- **Flexible Components**: Reusable CSS classes for consistent styling
- **Performance Optimized**: Efficient selectors and minimal CSS

### Key CSS Features
```css
/* Advanced Flexbox Usage */
.content {
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Responsive Media Queries */
@media (max-width: 600px) {
  .content { flex-direction: column; }
}

/* Custom Background Effects */
.bg {
  transform: skewY(-9deg);
  transform-origin: bottom left;
}
```

## 🚀 Featured Projects

1. **Battleship Game** - Interactive naval combat game with JavaScript
2. **Weather App** - Real-time weather data with API integration  
3. **Library Management** - Book tracking application with local storage
4. **Todo List** - Task management with priorities and due dates
5. **Restaurant Website** - Modern restaurant site with responsive design
6. **Tic Tac Toe** - Classic game with AI opponent

## 📱 Responsive Breakpoints

| Screen Size | Layout | Features |
|-------------|--------|----------|
| **Desktop** (>1200px) | Side-by-side hero, 3-column grid | Full project grid, large images |
| **Tablet** (600px-1200px) | Text wrapping, 2-column grid | Adaptive layouts, medium images |  
| **Mobile** (<600px) | Stacked layout, single column | Touch-optimized, large touch targets |

## 🎯 Performance Features

- **Optimized Images**: Modern formats (AVIF, WebP) for faster loading
- **Minimal JavaScript**: Focus on CSS for animations and interactions
- **Clean HTML**: Semantic structure for better SEO and accessibility
- **Efficient CSS**: Optimized selectors and minimal redundancy

## 📈 Browser Support

- ✅ Chrome (90+)
- ✅ Firefox (90+)  
- ✅ Safari (14+)
- ✅ Edge (90+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Tifa004/Homepage.git
   cd Homepage
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🌐 Deployment

This portfolio is deployed using **GitHub Pages**:
- Automatic deployment from the main branch
- Custom domain support available
- HTTPS enabled by default

## 🤝 Contributing

Interested in contributing? Great! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Mostafa Sakr** - Web Developer

- 📧 Email: mostafasakr01@hotmail.com
- 📱 Phone: +201273964860
- 💼 LinkedIn: [Mostafa Sakr](https://www.linkedin.com/in/mostafa-sakr-862541243)
- 🐙 GitHub: [@Tifa004](https://github.com/Tifa004)

---

⭐ If you found this project helpful, please give it a star on GitHub!

## 🎉 Acknowledgments

- Google Fonts for typography
- Inspiration from modern web design trends
- Open source community for tools and resources

---

*Built with ❤️ and lots of CSS*