# Velvet Pour - Cocktail Landing Page

A modern, animated cocktail bar landing page built with React, Vite, and GSAP. This project showcases a beautiful, interactive website for "Velvet Pour" cocktail bar with smooth animations, responsive design, and an engaging user experience.

## 🍹 Features

-   **Interactive Hero Section**: Animated text with GSAP SplitText and video background
-   **Cocktail Menu**: Interactive carousel showcasing different cocktails with detailed descriptions
-   **About Section**: Image gallery with smooth scroll animations
-   **Art Section**: Creative visual presentation with masked images
-   **Contact Information**: Store details, hours, and social media links
-   **Responsive Design**: Mobile-first approach with Tailwind CSS
-   **Smooth Animations**: GSAP-powered scroll triggers and timeline animations
-   **Modern UI/UX**: Clean, elegant design with custom fonts and gradients

## 🛠️ Tech Stack

-   **Frontend Framework**: React 19.1.0
-   **Build Tool**: Vite 6.3.5
-   **Styling**: Tailwind CSS 4.1.7
-   **Animations**: GSAP 3.13.0 with ScrollTrigger and SplitText plugins
-   **Responsive Design**: react-responsive 10.0.1
-   **Development**: ESLint for code quality

## 📁 Project Structure

```
gsap_cocktails-main/
├── public/
│   ├── images/          # All project images and assets
│   ├── fonts/           # Custom fonts (Modern Negra)
│   └── videos/          # Video assets for hero section
├── src/
│   ├── components/      # React components
│   │   ├── About.jsx    # About section with image gallery
│   │   ├── Art.jsx      # Art showcase section
│   │   ├── Cocktails.jsx # Cocktail menu display
│   │   ├── Contact.jsx  # Contact information
│   │   ├── Hero.jsx     # Hero section with video
│   │   ├── Menu.jsx     # Interactive cocktail carousel
│   │   └── Navbar.jsx   # Navigation component
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles and Tailwind configuration
├── constants/
│   └── index.js         # Data constants and configuration
├── package.json
├── vite.config.js
└── index.html
```

## 🚀 Getting Started

### Prerequisites

-   Node.js (version 16 or higher)
-   npm or yarn package manager

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/MUSTAFAREZA47/velvet-pour.git
    cd gsap_cocktails-main
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Start the development server**

    ```bash
    npm run dev
    ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

### Available Scripts

-   `npm run dev` - Start development server
-   `npm run build` - Build for production
-   `npm run preview` - Preview production build
-   `npm run lint` - Run ESLint for code quality

## 🎨 Key Components

### Hero Section

-   Animated title with character-by-character reveal
-   Video background with scroll-triggered playback
-   Parallax leaf decorations
-   Responsive design for mobile and desktop

### Cocktail Menu

-   Interactive carousel with navigation arrows
-   Tab-based cocktail selection
-   Smooth transitions between cocktails
-   Detailed descriptions and pricing

### About Section

-   Image grid with staggered animations
-   Customer rating display
-   Scroll-triggered content reveals

### Art Section

-   Creative masked image presentation
-   Radial gradient background
-   Large typography with visual impact

## 🎭 Animation Features

-   **GSAP ScrollTrigger**: Elements animate as they enter the viewport
-   **SplitText**: Text animations with character and word splitting
-   **Timeline Animations**: Complex, sequenced animations
-   **Parallax Effects**: Background elements move at different speeds
-   **Video Integration**: Scroll-controlled video playback

## 📱 Responsive Design

The application is fully responsive with:

-   Mobile-first approach
-   Breakpoints for tablet and desktop
-   Optimized images and layouts for different screen sizes
-   Touch-friendly navigation elements

## 🎨 Custom Styling

-   **Custom Fonts**: Modern Negra and DM Serif Text
-   **Color Palette**: Black background with yellow accents
-   **Gradients**: Text gradients and radial backgrounds
-   **Custom Utilities**: Tailwind CSS custom utilities for common patterns

## 📊 Data Structure

The application uses a centralized data structure in `constants/index.js`:

-   Navigation links
-   Cocktail and mocktail lists
-   Store information and hours
-   Social media links
-   Profile images and feature lists

## 🔧 Configuration

### Vite Configuration

-   React plugin for JSX support
-   Tailwind CSS integration
-   Optimized build settings

### Tailwind CSS

-   Custom color variables
-   Custom font families
-   Component-specific styles
-   Utility classes for common patterns

## 🚀 Deployment

To deploy this application:

1. **Build the project**

    ```bash
    npm run build
    ```

2. **Deploy the `dist` folder** to your preferred hosting service:
    - Vercel
    - Netlify
    - GitHub Pages
    - Any static hosting service

## 📝 License

This project is for educational and portfolio purposes. Please ensure you have the right to use any assets (images, fonts, videos) in your own projects.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Contact

For questions or support, please contact the development team.

---

**Note**: This is a demo project showcasing modern web development techniques with React, GSAP, and Tailwind CSS. The cocktail bar "Velvet Pour" is fictional and created for demonstration purposes.
