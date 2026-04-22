# My Portfolio Website

A modern, responsive single-page portfolio website built with HTML5, CSS3, and Vanilla JavaScript.

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Styling with responsive design
├── js/
│   └── script.js       # JavaScript functionality
├── assets/
│   └── profile.jpg     # Profile picture (add your own)
└── README.md           # This file
```

## ✨ Features

- **Responsive Design**: Mobile-first approach, works beautifully on all screen sizes
- **Hero Section**: Eye-catching introduction with your name, role, and value statement
- **Call-to-Action Buttons**: "View Projects" and "Contact Me" buttons with smooth scrolling
- **Social Links**: Quick links to GitHub, LinkedIn, Twitter, and more
- **Fixed Navigation**: Sticky navbar with smooth scroll behavior
- **Modern UI**: Gradient accents, smooth animations, and clean typography
- **Mobile Menu**: Hamburger menu for mobile devices

## 🎨 Customization Guide

### 1. **Update Your Information**

Edit `index.html`:
- Line 45: Replace `Your Name` with your actual name
- Line 46: Update your role/subtitle (e.g., "Computer Science Student | Aspiring Data Scientist")
- Line 47-49: Update your value statement (2 lines describing your passion)
- Lines 102-117: Update social links with your GitHub, LinkedIn, Twitter URLs

### 2. **Add Your Profile Picture**

1. Create an `assets/` folder if it doesn't exist
2. Add your profile picture as `profile.jpg` (or PNG)
3. For best results, use a square image (500x500px recommended)

### 3. **Change Colors**

Edit the CSS variables in `css/styles.css` (lines 7-19):
```css
--primary-color: #6366f1;        /* Main brand color */
--secondary-color: #ec4899;      /* Accent color */
--text-dark: #1f2937;            /* Dark text */
--text-light: #6b7280;           /* Light gray text */
--bg-light: #f9fafb;             /* Light background */
```

### 4. **Customize Fonts**

The site uses "Poppins" from Google Fonts. To change:
1. Visit https://fonts.google.com
2. Select your font
3. Replace the font link in `index.html` (lines 11-12)
4. Update the font-family in `css/styles.css` (line 28)

### 5. **Add More Sections**

To add Projects or Contact sections, follow the existing structure:
```html
<section id="section-name" class="section-class">
    <div class="container">
        <!-- Your content here -->
    </div>
</section>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px to 1023px
- **Mobile**: Below 480px

All sections are fully responsive and mobile-optimized.

## 🚀 Getting Started

1. Extract all files to your portfolio folder
2. Open `index.html` in your web browser
3. Replace placeholder content with your information
4. Add your profile picture
5. Customize colors and fonts as desired
6. Add your social media URLs

## 🔗 Deployment Options

- **GitHub Pages**: Free hosting directly from your GitHub repository
- **Netlify**: Drag and drop deployment
- **Vercel**: Zero-config deployment
- **Any web hosting**: Upload files via FTP

## 📝 Future Enhancements

Consider adding:
- Projects showcase with images and descriptions
- Skills section with visual progress bars
- Experience/Work history timeline
- Contact form with backend
- Blog section
- Dark mode toggle
- Testimonials section

## 💡 Tips

- Keep your portfolio clean and focused
- Use high-quality images
- Make sure links work (especially social media)
- Test on different devices and browsers
- Keep content up-to-date
- Add a contact form for inquiries

## 📄 License

Feel free to use this template for your portfolio!

