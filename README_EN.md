# Dois Irmãos Marmoraria 🏛️

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Bootstrap_Icons-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap Icons"/>
</p>

<p align="center">
  <a href="#-about-the-project">About</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-features">Features</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-project-structure">Project Structure</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-author">Author</a> •
  <a href="README.md">Português</a>
</p>

## 📋 About the Project

An elegant and responsive corporate website for **Dois Irmãos Marmoraria**, a company specializing in high-quality marble and granite products. The project showcases best practices in modern web development, combining aesthetic design with functional user experience.

The website features a sophisticated layout with interactive elements like automatic image sliders and product carousels, designed to highlight the beauty and craftsmanship of marble and granite applications in various environments.

## 🚀 Technologies

This project leverages several modern web technologies:

- **HTML5** - Semantic markup for content structure
- **CSS3** - Advanced styling with flexbox and responsive design
- **JavaScript (Vanilla)** - Custom interactive elements without frameworks
- **Tailwind CSS** - Utility-first CSS framework with custom configuration
- **GSAP & ScrollTrigger** - Animation library for smooth scrolling effects
- **Bootstrap Icons** - Comprehensive icon library
- **Google Maps Integration** - Location embedding

## ✨ Features

### 1. Responsive Header with Navigation
- Fixed top menu with smooth scrolling to sections
- Mobile-friendly collapsible menu
- Dynamic background that expands on scroll

### 2. Hero Section with Parallax Effect
- Fullscreen image with parallax scrolling effect
- Elegant gradient overlay
- Prominent call-to-action button

### 3. Interactive Product Carousel
- Custom-built carousel displaying 3 products at once
- Navigation controls (previous/next buttons)
- Dot indicators for slide position
- Automatic rotation with configurable timing

### 4. Company Profile Section
- Elegant presentation of company values and history
- Optimized content layout for all device sizes

### 5. Location Integration
- Google Maps embedding for physical store location
- Contact information with clickable elements

### 6. Direct Contact Options
- WhatsApp integration for instant communication
- Contact button in the homepage section
- Floating WhatsApp contact button

### 7. Professional Footer
- Company information and navigation links
- Social media integration
- Copyright information

## 🔧 Getting Started

### Prerequisites
- Any modern web browser
- Basic understanding of web development (for modifications)
- Node.js and npm (optional, for Tailwind CSS development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/dois-irmaos-marmoraria.git
```

2. Navigate to the project directory:
```bash
cd dois-irmaos-marmoraria
```

3. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

### Development with Tailwind CSS (Optional)

1. Install dependencies:
```bash
npm install
```

2. Run Tailwind CSS build process:
```bash
npx tailwindcss -i ./css/tailwind.css -o ./css/tailwind-build.css --watch
```

## 📁 Project Structure

```
dois-irmaos-marmoraria/
├── assets/
│   ├── images/
│   │   ├── homepage/
│   │   │   ├── hero-image.jpg
│   │   │   ├── Cuba-esculpida.jpg
│   │   │   └── ...
│   │   └── logo.png
├── css/
│   ├── index.css
│   ├── tailwind-build.css
│   └── tailwind.css
├── scripts/
│   └── utils.js
├── index.html
├── index.js
├── tailwind.config.js
└── README.md
```

## 🔍 Technical Details

### Custom JavaScript Components

The project includes several custom JavaScript components:

- **SlideShow Class**: Manages carousel functionality with configurable auto-rotation
- **Modal Class**: Handles popup dialogs for information and forms
- **Dropdown Class**: Controls dropdown menu behavior
- **Parallax Effects**: Custom scrolling effects for the hero image

### Tailwind CSS Configuration

The project uses a customized Tailwind CSS setup:

- Custom prefix (`tw-`) to avoid conflicts with other CSS
- Extended color palette with brand colors
- Responsive breakpoints for various device sizes

### Performance Optimizations

- Lazy loading for images
- Efficient DOM manipulation
- Optimized asset loading

## 👥 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 👨‍💻 Author

**Estêvão Segatto Vieira**  
Full Stack Developer | Specialist in APIs and Responsive Interfaces

---

<p align="center">
  Made with ❤️ for Dois Irmãos Mármore e Granito
</p>
