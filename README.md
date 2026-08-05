# Vibe Coding - Theme Gallery Landing Page

A modern, responsive landing page with an extensive theme gallery. Switch between 24+ beautiful themes instantly with live updates across the entire page.

## 🌟 Features

- **24+ Modern Themes** organized into 8 categories:
  - Glass & Glow
  - Dark & Neon
  - Light & Minimal
  - Pastel & Premium
  - Nature & Earth
  - Warm & Corporate

- **Instant Theme Switching**: Click any theme to see real-time updates across the entire page
- **Search Filter**: Find themes by name, description, or category
- **100% Responsive**: Works beautifully on desktop, tablet, and mobile devices
- **Glassmorphism UI**: Modern design with frosted glass effects and smooth animations
- **Zero Dependencies**: Pure HTML, CSS, and vanilla JavaScript

## 🎨 Theme Categories

### Glass & Glow
- **Aurora**: Creative, smooth, glowing
- **Glass**: Transparent, ethereal

### Dark
- **Midnight**: Deep, elegant dark
- **Graphite**: Neutral, professional dark

### Light
- **Daylight**: Clean, bright, minimal
- **Arctic**: Cool, pure

### Neon
- **Neon Pulse**: High contrast, vibrant
- **Cyberpunk**: Dark, electronic, rebellious
- **Neon Lime**: Bright, bold

### Pastel
- **Pastel Bloom**: Soft, sweet, modern
- **Lavender**: Dreamy, gentle
- **Rose Quartz**: Soft, pink, elegant

### Nature
- **Mint Fresh**: Cool, clean, refreshing
- **Ocean Wave**: Ocean blue, calm
- **Forest**: Deep, green, stable

### Warm
- **Sunset**: Warm, vibrant, emotional
- **Cherry**: Energy, standout
- **Ember**: Fire, depth

### Premium
- **Luxury Gold**: Upscale, refined
- **Plum**: Deep, artistic, sophisticated

### Minimal
- **Minimal Mono**: Monochrome, focused
- **Paper**: Minimalist like paper

### Earth
- **Sandstone**: Warm, gentle, natural

### Corporate
- **Blue Steel**: Professional, modern

## 🚀 Live Demo

Visit: **https://trungdoanhong.github.io/vibe-coding/**

## 💻 Local Development

Simply open `index.html` in your web browser:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 🎯 How to Use

1. **Browse Themes**: Scroll through the left sidebar to see all available themes
2. **Search**: Use the search box to filter themes by name or description
3. **Switch**: Click on any theme to instantly apply it
4. **Active Theme**: The current theme is highlighted with a glow effect

## 🛠️ Customization

### Adding New Themes

Edit the `themes` array in the `<script>` section:

```javascript
{
  name: "Your Theme",
  group: "Category",
  description: "Brief description",
  icon: "Y",
  vars: {
    bg: "#ffffff",
    bg2: "#f0f0f0",
    surface: "rgba(0,0,0,0.05)",
    // ... other color variables
  }
}
```

### Modifying Colors

Update CSS variables in the `setTheme()` function to customize which elements respond to theme changes.

## 📱 Responsive Breakpoints

- **Desktop**: 2-column layout (sidebar + main content)
- **Tablet** (1100px and below): Single column
- **Mobile** (720px and below): Optimized touch experience with reduced stats grid

## 🎨 Design System

The page uses a sophisticated design system with:

- **CSS Custom Properties** for dynamic theming
- **Glassmorphism Effects**: Backdrop blur + transparency
- **Smooth Animations**: 0.2s transitions for interactions
- **Responsive Typography**: `clamp()` for fluid sizing
- **Modern Color Blending**: `color-mix()` for gradient overlays

## 📄 License

Free to use and modify for personal or commercial projects.

## 🤝 Contributing

Feel free to suggest new themes or improvements!

---

Made with ❤️ for designers and developers who love beautiful, modern interfaces.
