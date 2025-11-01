# Sundown Studio - Multi-disciplinary Design Website

A modern, interactive web experience showcasing a multi-disciplinary creative studio. This project features smooth scrolling animations, dynamic image galleries, and responsive design principles.

## 🌟 Features

- **Smooth Scroll Experience**: Implemented using Locomotive Scroll for buttery-smooth page transitions
- **Animated Loader**: Eye-catching text sequence animation on page load
- **Interactive Navigation**: Full-screen menu with smooth transitions
- **Dynamic Image Gallery**: Hover-triggered image previews with custom positioning
- **Swiper Integration**: Touch-enabled carousel for project showcases
- **Responsive Design**: Fully optimized for mobile and desktop devices
- **Custom Animations**: CSS keyframe animations for hero shapes and moving text
- **Gooey Effects**: Animated gradient blobs for visual interest

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom animations, flexbox, and responsive design
- **JavaScript**: Vanilla JS for interactions and animations
- **Locomotive Scroll**: Smooth scrolling library
- **Swiper.js**: Modern touch slider
- **Custom Fonts**: Neue Haas Display family

## 📁 Project Structure

```
sundown-studio/
│
├── index.html          # Main HTML structure
├── style.css           # Core styling and animations
├── script.js           # JavaScript functionality
├── icon.png            # Favicon
├── video.mp4           # Hero section video
│
├── fonts/
│   ├── NeueHaasDisplayMediu.ttf
│   ├── NeueHaasDisplayLight.ttf
│   └── NeueHaasDisplayRoman.ttf
│
└── test files/
    ├── test.html       # Testing environment
    ├── test.css        # Test styles
    └── test.js         # Test scripts
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local development server (optional but recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sundown-studio.git
```

2. Navigate to the project directory:
```bash
cd sundown-studio
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

4. Visit `http://localhost:8000` in your browser

## 💡 Key Functionalities

### 1. Loader Animation
Displays sequential text animations before revealing the main content
```javascript
loaderAnimation() // Hides loader after 4.2 seconds
```

### 2. Image Gallery Interaction
Hover over project titles to see full-size images
```javascript
page4Animation() // Manages fixed image display on hover
```

### 3. Smooth Scrolling
Locomotive Scroll implementation for enhanced UX
```javascript
const scroll = new LocomotiveScroll({
    el: document.querySelector('#main'),
    smooth: true
});
```

### 4. Full-Screen Menu
Toggle navigation with smooth transitions
```javascript
menuAnimation() // Opens/closes full-screen menu overlay
```

## 🎨 Design Highlights

- **Color Palette**: Warm earth tones (#EFEAE3) with vibrant orange accents (#FE320A)
- **Typography**: Neue Haas Display for clean, modern aesthetics
- **Animations**: Smooth transitions, blur effects, and gradient animations
- **Layout**: Responsive grid system with flexible components

## 📱 Responsive Breakpoints

- **Desktop**: Full-featured experience with all animations
- **Mobile** (max-width: 600px): Optimized layout with adjusted typography and spacing

## 🔧 Customization

### Changing Colors
Update the primary color in `style.css`:
```css
/* Orange accent color */
#FE320A → Your color

/* Background color */
#EFEAE3 → Your color
```

### Modifying Animations
Adjust animation duration in CSS:
```css
@keyframes move {
    animation-duration: 10s; /* Change duration */
}
```

### Adding Projects
Add new elements to `#elem-container` in `index.html`:
```html
<div class="elem" data-image="your-image-url">
    <div class="overlay"></div>
    <h2>Project Name</h2>
</div>
```

## 📊 Performance Optimizations

- Lazy loading for images
- CSS animations using `transform` for GPU acceleration
- Minimal JavaScript for faster load times
- Optimized video compression for hero section

## 🐛 Known Issues

- Locomotive Scroll may have conflicts with certain mobile browsers
- Video autoplay might be blocked on some devices (browser policy)

## 🤝 Contributing

This is a learning project recreating production-grade design. Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📄 License

This project is for educational purposes. Original design inspiration from Sundown Studio.

## 👨‍💻 Developer

Created as part of frontend development learning journey, showcasing skills in:
- Modern JavaScript
- CSS animations
- Responsive design
- Third-party library integration

---

**Note**: This is a recreation project for portfolio purposes, demonstrating ability to build production-grade frontend experiences.
