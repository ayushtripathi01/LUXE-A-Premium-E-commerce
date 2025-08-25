# LUXE - Premium Fashion E-commerce Website

A sophisticated luxury fashion e-commerce website built with modern web technologies.

## Overview

LUXE is a fully functional premium fashion website that delivers an immersive shopping experience with elegant design and smooth functionality.

## Features

### Design
- Luxury aesthetic with dark themes and golden accents
- Smooth animations and hover effects
- Glassmorphism navigation with backdrop blur
- Responsive design for all devices
- Premium typography using Georgia serif font

### Functionality
- Product catalog with 10 luxury items
- Category filtering (Men, Women, Accessories)
- Shopping cart with quantity controls
- Real-time cart updates and totals
- Checkout process with order confirmation
- Contact form for consultation booking

### Sections
- Hero section with brand introduction
- Product collection with filtering
- About section with brand story
- Contact section with booking form
- Professional footer

## Products
- **Men's Fashion**: Cashmere Overcoats, Italian Leather Shoes, Tailored Suits, Merino Sweaters
- **Women's Fashion**: Silk Evening Dresses, Wool Blazers, Designer Scarves
- **Accessories**: Pearl Jewelry, Swiss Watches, Luxury Handbags

## Technology Stack
- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with animations
- **Vanilla JavaScript** - Pure JS functionality
- **Responsive Design** - Mobile-first approach

## Getting Started

### Quick Start
1. Download or clone the repository
2. Open `index.html` in your browser
3. Start shopping!

### Local Server (Optional)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Navigate to localhost:8000 or localhost:3000
```

## File Structure
```
luxe-ecommerce/
├── index.html          # Main application file
└── README.md          # This file
```

## Key Features Breakdown

### Shopping Cart
- Add items with single click
- Adjust quantities with +/- buttons
- Remove items from cart
- Real-time total calculation
- Sliding cart sidebar

### Product Filtering
- Filter by All, Men, Women, or Accessories
- Dynamic product display
- Smooth category transitions

### Contact Form
- Personal styling consultation requests
- Form validation
- Service selection dropdown
- Professional confirmation messages

## Customization

### Change Colors
Find and replace `#c9a96e` (luxury gold) with your preferred color in the CSS.

### Add Products
Add new items to the `products` array in JavaScript:
```javascript
{
  id: 11,
  name: "Product Name",
  price: 999,
  category: "men|women|accessories",
  image: "custom",
  icon: "👕"
}
```

## Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- Mobile browsers

## Performance
- Single HTML file with embedded CSS and JS
- No external dependencies
- Fast loading and responsive
- Optimized animations

## License
MIT License - Feel free to use for personal or commercial projects.

## Contact
For questions or suggestions, feel free to reach out or create an issue.

## Future Enhancements
- User authentication
- Payment integration
- Product reviews
- Wishlist feature
- Advanced filtering
- Order tracking

---

**Built with modern web technologies for a premium shopping experience.**
