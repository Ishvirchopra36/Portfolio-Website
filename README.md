# Personal Portfolio Website

A modern, responsive portfolio website showcasing my projects, skills, experience, and education as a Computer Science student.

## Live Demo

**[View Live Portfolio](https://yourwebsite.com)**

## Screenshots

<div align="center">

### Hero Section

![Hero Section](screenshots/hero_section.png)
*Landing page with particle.js animation and typing effect*

### About Me

![About Section](screenshots/about_section.png)
*Personal introduction and resume download*

### Skills Section

![Skills](screenshots/skills_section.png)
*Technical skills showcase with icons*

### Projects Portfolio

![Projects](screenshots/projects_section.png)
*Featured projects with live demos and GitHub links*

### Contact Form

![Contact](screenshots/contact_section.png)
*Functional contact form with EmailJS integration*

### Mobile Responsive

![Mobile View](screenshots/mobile_view.png)
*Responsive design on mobile devices*

</div>

---

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Animations**: 
  - Particle.js animated background
  - Typed.js dynamic text effects
  - Vanilla Tilt 3D hover effects
  - ScrollReveal smooth section animations
- **Sections**:
  - Home with animated introduction
  - About Me with personal background
  - Skills showcase with visual icons
  - Education timeline
  - Projects portfolio with GitHub links
  - Experience timeline
  - Contact form with EmailJS integration
- **Social Media Integration**: Quick links to LinkedIn, GitHub, Twitter, YouTube, and Instagram
- **Smooth Navigation**: Sticky navbar with smooth scrolling
- **Contact Form**: Functional contact form using EmailJS

## Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Custom styling with animations and transitions
- **JavaScript**: Interactive functionality and dynamic content

### Libraries & Frameworks
- **[Particle.js](https://vincentgarreau.com/particles.js/)**: Interactive particle background
- **[Typed.js](https://mattboldt.com/demos/typed-js/)**: Typing animation effects
- **[Vanilla Tilt.js](https://micku7zu.github.io/vanilla-tilt.js/)**: 3D tilt hover effects
- **[ScrollReveal](https://scrollrevealjs.org/)**: Scroll-based animations
- **[EmailJS](https://www.emailjs.com/)**: Contact form email functionality
- **[Font Awesome](https://fontawesome.com/)**: Icon library

### Hosting
- **Azure Static Web Apps**: Cloud hosting and deployment

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for customization)

### Installation

1. **Clone the repository**
```
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. **Open in browser**
```
# Simply open index.html in your browser
# OR use a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

### Customization

1. **Update Personal Information**
   - Edit `index.html` to change your name, description, and contact details
   - Replace social media links with your own

2. **Add Your Projects**
   ```
   <div class="box">
     <img src="path/to/your/image.jpg" alt="Project Name" />
     <div class="content">
       <div class="tag">
         <h3>Your Project Name</h3>
       </div>
       <div class="desc">
         <p>Project description here</p>
         <div class="btns">
           <a href="demo-link" class="btn"><i class="fas fa-eye"></i> View</a>
           <a href="github-link" class="btn">Code <i class="fas fa-code"></i></a>
         </div>
       </div>
     </div>
   </div>
   ```

3. **Update Skills**
   - Modify the skills section in `index.html`
   - Add skill icons from [Icons8](https://icons8.com/) or Font Awesome

4. **Configure Email (EmailJS)**
   - Sign up at [EmailJS](https://www.emailjs.com/)
   - Create email service and template
   - Update EmailJS credentials in `script.js`:
   ```javascript
   emailjs.init("YOUR_USER_ID");
   emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", params);
   ```

5. **Customize Styling**
   - Edit `./assets/css/style.css` to change colors, fonts, and layouts
   - Modify particle.js settings in `./assets/js/app.js`

## Project Structure

```
portfolio/
│
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   ├── script.js       # Main JavaScript
│   │   ├── particles.min.js # Particle.js library
│   │   └── app.js          # Particle.js configuration
│   └── images/             # Images and icons
│       ├── waving.png
│       ├── pfplinkedin.JPG
│       └── ...
├── projects.html           # Projects page (optional)
├── experience.html         # Experience page (optional)
└── README.md
```

## Color Scheme

- **Primary**: `#27ae60` (Green)
- **Background**: `#0a0a0a` (Dark)
- **Text**: `#fff` (White)
- **Accent**: Custom as per sections

*Customize these in `style.css` to match your personal brand*

## Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px

## Deployment

### Azure Static Web Apps

This portfolio is deployed on Azure Static Web Apps for fast, secure, and scalable hosting.

**Deployment Steps:**

1. **Push to GitHub**
```
git add .
git commit -m "Deploy portfolio"
git push origin main
```

2. **Deploy to Azure**
   - Go to [Azure Portal](https://portal.azure.com/)
   - Create new Static Web App
   - Connect to your GitHub repository
   - Configure build settings:
     - App location: `/`
     - Output location: `/`
   - Azure automatically deploys on every push

**Automatic Deployment:**
- Every push to `main` branch triggers automatic deployment
- Preview deployments for pull requests
- Custom domain support available

### Alternative Deployment Options

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE11 (partial support - some animations may not work)

## Performance Optimization

- Minified CSS and JavaScript
- Optimized images (WebP format recommended)
- Lazy loading for images
- CDN for external libraries

## Known Issues

- Contact form requires EmailJS configuration
- Right-click disabled (can be removed if needed)
- Some animations may be slow on older devices

## Future Enhancements

- [ ] Add dark/light theme toggle
- [ ] Implement blog section
- [ ] Add project filtering by technology
- [ ] Create admin panel for easy content updates
- [ ] Add testimonials section
- [ ] Implement analytics (Google Analytics)
- [ ] Add loading screen/preloader
- [ ] Create multilingual support
- [ ] Add resume download functionality
- [ ] Implement project search functionality

## License

This project is open source

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/portfolio/issues).

## Inspiration & Credits

- Design inspiration from various developer portfolios
- Libraries: Particle.js, Typed.js, Vanilla Tilt, ScrollReveal
- Icons: Font Awesome, Icons8
- Fonts: Google Fonts

## Contact

**Ishvir Chopra** - ishvir.chopra@gmail.com

Portfolio: ishvirchopra35.tech   
LinkedIn: https://www.linkedin.com/in/ishvir-chopra-23758b2a8/  


### Quick Start Commands

```
# Clone the repo
git clone https://github.com/yourusername/portfolio.git

# Navigate to directory
cd portfolio

# Open in browser
open index.html  # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

Made with ❤️ by Ishvir Chopra
