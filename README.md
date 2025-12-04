# 🚀 Injamul Haque - MERN Stack Developer Portfolio

## 📋 Overview

A stunning, responsive portfolio website built with modern web technologies to showcase professional work, skills, and contact information. This portfolio demonstrates advanced frontend development capabilities with smooth animations, interactive components, and a modern dark theme design.

## ✨ Key Features

### 🎨 Design & UI/UX

- **Modern Dark Theme** - Professional dark color scheme with blue accents
- **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations** - Engaging micro-interactions using Framer Motion
- **Component-Based Architecture** - Clean, maintainable code structure
- **Professional Typography** - Clean, readable font hierarchy

### 📱 Sections

- **Hero Section** - Eye-catching landing with call-to-action buttons
- **About Me** - Professional introduction with skills statistics
- **Skills** - Comprehensive skill showcase with progress bars
- **Projects** - Filterable project gallery with live demos
- **Contact** - Functional contact form with social links
- **Footer** - Quick navigation and contact information

### ⚡ Technical Features

- **Smooth Scrolling** - Seamless navigation between sections
- **Interactive Elements** - Hover effects, transitions, and animations
- **Contact Form** - Functional form with validation
- **Social Media Integration** - Links to professional profiles
- **Scroll-to-Top** - Easy navigation with back-to-top button
- **Mobile Menu** - Responsive hamburger menu for mobile devices

## 🛠️ Technologies Used

### Frontend Stack

- **React 18.3.1** - Component-based UI framework
- **React Router DOM 7.1.0** - Client-side routing with HashRouter
- **Tailwind CSS 3.4.17** - Utility-first CSS framework
- **Framer Motion 11.0.8** - Animation library
- **React Icons 5.4.0** - Icon library

### Development Tools

- **Vite 5.4.2** - Fast build tool and development server
- **ESLint** - Code linting and formatting
- **PostCSS** - CSS post-processing
- **Autoprefixer** - CSS vendor prefixing

### Additional Libraries

- **@supabase/supabase-js** - Backend integration (ready)
- **ECharts** - Data visualization components
- **date-fns** - Date manipulation utilities

## 📁 Project Structure

```
portfolio/
├── src/
│   ├── components/          # React components
│   │   ├── Hero.jsx        # Landing hero section
│   │   ├── About.jsx       # About me section
│   │   ├── Skills.jsx      # Skills showcase
│   │   ├── Projects.jsx    # Projects gallery
│   │   ├── Contact.jsx     # Contact form & info
│   │   ├── Footer.jsx      # Site footer
│   │   └── Navbar.jsx      # Navigation bar
│   ├── common/
│   │   └── SafeIcon.jsx    # Safe icon component wrapper
│   ├── App.jsx             # Main application component
│   ├── App.css             # Global Tailwind styles
│   ├── index.css           # Custom CSS & utilities
│   └── main.jsx            # Application entry point
├── public/
│   └── favicon.svg         # Site favicon
├── index.html              # HTML template with SEO meta tags
├── package.json            # Project dependencies & scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── postcss.config.js       # PostCSS configuration
├── vite.config.js          # Vite build configuration
└── README.md               # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open in browser**
   - Navigate to `http://localhost:5173`
   - The app will automatically reload on changes

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run lint:error` - Run ESLint in quiet mode

## 🎯 Customization Guide

### Personal Information

Update these files with your information:

1. **Contact.jsx** - Update email, phone, and social links
2. **About.jsx** - Update personal description and stats
3. **Hero.jsx** - Update name, title, and social profiles
4. **Projects.jsx** - Add your own projects
5. **Skills.jsx** - Adjust skill levels and categories

### Styling Customization

- **Colors**: Modify Tailwind config for theme colors
- **Fonts**: Update `index.css` for custom fonts
- **Animations**: Adjust Framer Motion settings in components

### Adding Projects

1. Update `projects` array in `Projects.jsx`
2. Add project images to `/public/images/`
3. Include live demo and GitHub links
4. Set appropriate technologies and categories

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Mobile Considerations

- Collapsible navigation menu
- Touch-friendly buttons and links
- Optimized layouts for small screens
- Proper viewport meta tags

## 🎨 Design System

### Color Palette

- **Primary**: Blue shades (`blue-400`, `blue-600`)
- **Background**: Dark grays (`gray-800`, `gray-900`)
- **Text**: White and gray variations
- **Accent**: Blue for interactive elements

### Typography

- **Headings**: Bold, large font sizes
- **Body**: Clean, readable sans-serif
- **Monospace**: For code and technical content

### Spacing & Layout

- Consistent spacing using Tailwind utilities
- Grid layouts for responsive design
- Proper component hierarchy

## 🔒 Best Practices Implemented

### Code Quality

- **Component-based architecture** - Reusable, maintainable components
- **Clean imports** - Organized and efficient imports
- **Consistent naming** - Clear, descriptive variable names
- **Error handling** - Safe icon wrapper component

### Performance

- **Optimized images** - Proper image sizing and formats
- **Lazy loading** - Components load as needed
- **Minimal dependencies** - Only essential packages
- **Build optimization** - Vite's fast build system

### Accessibility

- **Semantic HTML** - Proper heading hierarchy
- **ARIA labels** - Screen reader support
- **Focus states** - Keyboard navigation
- **Color contrast** - WCAG compliant colors

### SEO Optimization

- **Meta tags** - Complete SEO meta information
- **Open Graph** - Social media sharing
- **Structured data** - JSON-LD schema ready
- **Clean URLs** - HashRouter for deployment

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

### Deployment Options

- **Vercel** - Recommended for React apps
- **Netlify** - Easy deployment with CI/CD
- **GitHub Pages** - Free static hosting
- **AWS S3** - Scalable cloud hosting

### Environment Variables

Set up environment variables for:

- API endpoints (if using backend services)
- Analytics tracking codes
- Social media API keys

## 📧 Contact Information

- **Email**: itsinjamul@gmail.com
- **Phone**: +880 1683 239856
- **Location**: Dhaka, Bangladesh
- **LinkedIn**: [ninjamul-haque](https://linkedin.com/in/ninjamul-haque)
- **GitHub**: [Growthency](https://github.com/Growthency)

## 🤝 Contributing

This is a personal portfolio project. For suggestions or improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **React Team** - For the amazing React framework
- **Tailwind CSS** - For the utility-first CSS framework
- **Framer Motion** - For smooth animations
- **Unsplash** - For beautiful stock images
- **React Icons** - For comprehensive icon library

---

**Built with ❤️ and lots of ☕ by Injamul Haque**

_Last updated: January 2026_
