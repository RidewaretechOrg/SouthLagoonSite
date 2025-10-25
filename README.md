# KERA FRESH Website

![KERA FRESH](images/logo.png)

**A Taste of South India in Every Bite**
Official website for KERA FRESH - Authentic South Indian Instant Batters & Foods

---

## 🌟 About

KERA FRESH is a premium South Indian food brand offering preservative-free, stone-ground, naturally fermented instant batters and ready-to-cook foods. Founded in 2022 by South Lagoon Food Products LLC in Ajman, UAE, we serve families, restaurants, hotels, and food businesses across the UAE.

---

## 🚀 Live Website

Visit: [https://ridewaretechorg.github.io/SouthLagoonSite/](https://ridewaretechorg.github.io/SouthLagoonSite/)

---

## 📱 Website Pages

1. **Home** (`index.html`) - Main landing page with featured products, testimonials, and company overview
2. **About** (`about.html`) - Company story, mission, vision, and 6 core values
3. **Products** (`products.html`) - Complete product catalog with 7 products
4. **Recipes** (`recipes.html`) - 7 authentic South Indian recipes with step-by-step instructions
5. **Blog** (`blog.html`) - 6 blog articles about fermentation, tradition, and sustainability
6. **Contact** (`contact.html`) - Contact form, business information, and "Where to Buy" details
7. **FAQ** (`faq.html`) - 11 frequently asked questions in 4 categories
8. **Careers** (`careers.html`) - 4 open positions and company culture information

---

## 🎨 Tech Stack

### Frontend Framework
- **Tailwind CSS 3.x** - Utility-first CSS framework (via CDN)
- **HTML5** - Semantic markup
- **JavaScript (Vanilla)** - For interactions

### Libraries & Dependencies
- **AOS (Animate On Scroll)** - Scroll animations
- **Font Awesome 6.5.1** - Icons
- **Google Fonts (Lato)** - Typography

### Design Approach
- Mobile-first responsive design
- Progressive enhancement
- Accessibility-focused

---

## 🎨 Color Palette

```css
Primary Pink:    #df38b5  (kera-pink)
Magenta:         #e024c7  (kera-magenta)
Dark Pink:       #d63384  (kera-dark-pink)
Light Pink:      #f8a5c2  (kera-light-pink)
Lighter Pink:    #f4c2c2  (kera-lighter-pink)
Background 1:    #fff6f8  (kera-bg)
Background 2:    #fffafc  (kera-bg-alt)
Gold Accent:     #d4af37  (kera-gold)
```

---

## 📦 Installation & Setup

### Option 1: Direct Use (Recommended for Beginners)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ridewaretechorg/SouthLagoonSite.git
   cd SouthLagoonSite
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - No build process required (using CDN)

### Option 2: Local Development Server

Using Python:
```bash
python -m http.server 8000
# Visit http://localhost:8000
```

Using Node.js:
```bash
npx http-server
# Visit http://localhost:8080
```

Using VS Code:
- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

---

## 📁 Project Structure

```
SouthLagoonSite/
├── index.html              # Homepage
├── about.html              # About page
├── products.html           # Products page (7 products)
├── recipes.html            # Recipes page (7 recipes)
├── blog.html               # Blog page (6 articles)
├── contact.html            # Contact page
├── faq.html                # FAQ page
├── careers.html            # Careers page (4 positions)
│
├── images/                 # Image assets
│   ├── logo.png
│   ├── Kera 01.png        # Product showcase
│   ├── idlliiii.jpg       # Idli batter
│   ├── Medu-Vada.jpg      # Vada
│   ├── appam.jpg          # Appam
│   ├── coconut.jpg        # Coconut
│   ├── pinkidli.jpeg      # Marketing image
│   ├── home.4.png         # About section
│   ├── h4.jpg             # Recipe image
│   └── dosabatter.jpg     # Dosa
│
├── PROGRESS.md            # Development progress tracker
├── README.md              # This file
└── EDITED Kera Website Content 16th Oct.2025.txt  # Content source
```

---

## ✨ Features

### Design & UX
- ✅ Mobile-first responsive design
- ✅ Smooth scroll animations (AOS library)
- ✅ Sticky navigation with mobile menu
- ✅ Gradient backgrounds and modern effects
- ✅ Hover animations on cards
- ✅ Back-to-top button
- ✅ Marquee announcements

### Functionality
- ✅ WhatsApp integration
- ✅ Contact form (frontend validation)
- ✅ FAQ accordion
- ✅ Product showcase
- ✅ Testimonials
- ✅ E-commerce coming soon banner

### SEO & Performance
- ✅ Semantic HTML5
- ✅ Meta tags and descriptions
- ✅ Open Graph tags
- ✅ Optimized for search engines
- ✅ Fast loading (CDN-based)

---

## 🎯 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📱 Responsive Breakpoints

```css
Mobile:   < 768px   (sm)
Tablet:   768px+    (md)
Laptop:   1024px+   (lg)
Desktop:  1280px+   (xl)
```

---

## 🚀 Deployment

### GitHub Pages (Current)

Already deployed at: `https://ridewaretechorg.github.io/SouthLagoonSite/`

To update:
```bash
git add .
git commit -m "Update website"
git push origin main
```

### Alternative Hosting Options

#### Netlify
1. Sign up at [netlify.com](https://netlify.com)
2. Connect your GitHub repository
3. Deploy automatically on push

#### Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

#### Traditional Hosting (cPanel)
1. Upload all files via FTP
2. Ensure `index.html` is in root directory
3. Configure domain settings

---

## 🔧 Customization Guide

### Changing Colors

Edit the Tailwind config in each HTML file's `<head>` section:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'kera-pink': '#df38b5',      // Change this
                'kera-magenta': '#e024c7',   // Change this
                // ... etc
            }
        }
    }
}
```

### Changing Content

1. Open the HTML file you want to edit
2. Find the section to modify
3. Edit the text content
4. Save and refresh

### Adding New Pages

1. Copy an existing page (e.g., `about.html`)
2. Rename it (e.g., `new-page.html`)
3. Update the content
4. Add link to navigation menu in all pages

---

## 📞 Contact Information

**South Lagoon Food Products LLC**

- 📍 Address: PO Box 8143, Al Jurf Industrial-1, Ajman, UAE
- 📞 Phone: [+971 67674704](tel:+97167674704)
- ✉️ Email: [sales@south-lagoon.com](mailto:sales@south-lagoon.com)
- 🌐 Website: [www.south-lagoon.com](https://www.south-lagoon.com)

---

## 🛠️ Future Enhancements

### Planned Features
- [ ] E-commerce integration
- [ ] Backend for contact form
- [ ] Newsletter subscription
- [ ] Blog/Recipes section
- [ ] Customer reviews system
- [ ] Multi-language support (English/Arabic)
- [ ] Product search functionality
- [ ] Shopping cart

### Performance Optimization
- [ ] Set up Tailwind build process
- [ ] Image optimization and lazy loading
- [ ] Minify HTML/CSS/JS
- [ ] Implement CDN for static assets
- [ ] Add service worker for offline support

---

## 📝 Product List

1. **Idli & Dosa Batter** - Stone-ground, naturally fermented (1kg, 5kg)
2. **Vada Batter** - Ready to fry (1kg, 5kg)
3. **Appam Batter** - Gluten-free, lacy edges (1kg, catering)
4. **Malabar Parotta** - Half-cooked, flaky layers (5/10 pcs, bulk)
5. **Instant Poori** - Ready-to-fry wheat discs (10 pcs, bulk)
6. **Idiyappam** - String hoppers, heat & eat (Pack of 10)
7. **Grated Coconut** - Fresh, preservative-free (150g - 1kg, bulk)

---

## 🏆 Certifications

- ✅ HACCP Certified
- ✅ ISO 22000:2018 Certified

---

## 📄 License

© 2025 South Lagoon Food Products LLC. All rights reserved.

---

## 👨‍💻 Development

**Built with:** Tailwind CSS, HTML5, JavaScript
**Developed by:** Rideware Tech Org
**Last Updated:** October 20, 2025

---

## 🙏 Acknowledgments

- Font Awesome for icons
- AOS library for scroll animations
- Tailwind CSS for utility framework
- Google Fonts for Lato typography

---

## 📚 Documentation

For detailed development progress and technical specifications, see:
- [PROGRESS.md](PROGRESS.md) - Complete development timeline and features

---

## 🐛 Bug Reports

Found a bug? Please contact:
- Email: sales@south-lagoon.com
- Or create an issue in the GitHub repository

---

## ⭐ Show Your Support

If you like KERA FRESH products, give us a star on GitHub!

---

**KERA FRESH** - *Where Tradition Meets Convenience*
*A Taste of Home, Wherever You Are* 🌸
