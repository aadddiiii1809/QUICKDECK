# QuickDeck eCommerce Website Starter Template

A professional, responsive eCommerce website template built with pure HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Blue Theme**: Professional color scheme matching QuickDeck branding
- **3 Pages**: Home, About, and Contact pages
- **Product Showcase**: Ready-to-use product grid with hover effects
- **Smooth Scrolling**: "Shop Now" button smoothly scrolls to products section
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Social Media Links**: Footer with social media icon placeholders
- **SEO Ready**: Proper meta tags and semantic HTML

## Pages Included

1. **index.html** - Homepage with banner, features, and product showcase
2. **about.html** - About page with company story and values
3. **contact.html** - Contact page with form and business details

## Folder Structure

```
quickdeck-website/
├── index.html
├── about.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── banner.jpg (add your banner image here)
└── README.md
```

## Setup Instructions

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify

1. Create a free account at [Netlify](https://www.netlify.com)
2. Drag and drop the entire folder to Netlify
3. Your site will be live instantly with a custom URL

### Option 3: Local Testing

1. Open `index.html` directly in your browser, or
2. Use a local server:
   ```bash
   python -m http.server 5000
   ```
3. Visit `http://localhost:5000` in your browser

## Customization Guide

### Adding Your Banner

The template includes a placeholder banner (banner.svg) that displays a blue gradient.

To add your custom banner:
1. Place your banner image in the `assets/` folder
2. Name it `banner.jpg` or `banner.png`
3. Update `index.html` - change `src="assets/banner.svg"` to `src="assets/banner.jpg"`
4. Recommended size: 1920x500px
5. The banner will overlay on the blue gradient background with 30% opacity

### Updating Contact Information

Edit the footer section in all HTML files to update:
- Address
- Phone number
- Email address
- Social media links

### Adding Products

In `index.html`, find the `<section class="products">` and duplicate the product card structure:

```html
<div class="product-card">
    <div class="product-image">
        <img src="your-image.jpg" alt="Product Name">
        <div class="product-overlay">
            <button class="btn-secondary">Quick View</button>
        </div>
    </div>
    <div class="product-info">
        <h3>Product Name</h3>
        <p class="product-description">Description here</p>
        <div class="product-price">
            <span class="price">₹999</span>
            <span class="original-price">₹1,499</span>
        </div>
        <button class="btn-add-cart">Add to Cart</button>
    </div>
</div>
```

### Changing Colors

Edit `css/style.css` and update the CSS variables at the top:

```css
:root {
    --primary-blue: #1e40af;
    --light-blue: #3b82f6;
    --dark-blue: #1e3a8a;
    --accent-blue: #60a5fa;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (Flexbox & Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons (CDN)
- Google Fonts (Poppins)

## Future Enhancements

You can extend this template by adding:
- Shopping cart functionality
- Product detail pages
- User authentication
- Payment gateway integration
- Product search and filtering
- Customer reviews section
- Newsletter subscription
- Blog section

## License

Free to use for personal and commercial projects.

## Support

For questions or support, contact: info@quickdeck.com

---

**QuickDeck** - Your Premier eCommerce Destination
