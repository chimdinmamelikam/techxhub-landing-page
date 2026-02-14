# TechXHub 🚀

A modern, responsive landing page for a premium tech gadgets e-commerce store. Built with pure HTML, CSS, and JavaScript.

![TechXHub Preview](./preview.png)

## 🌟 Live Demo

**[View Live Site](https://techxhub-landing-page.vercel.app)**

## ✨ Features

- 🛒 **Full Shopping Cart Functionality** - Add/remove items, adjust quantities, view total
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- 🎨 **Modern UI/UX** - Clean blue and white design with smooth animations
- ⚡ **Lightning Fast** - Optimized performance with vanilla JavaScript
- 💳 **Product Showcase** - Six featured tech products with detailed info
- ⭐ **Customer Reviews** - Social proof section with testimonials
- 📧 **Contact Form** - Functional form with validation
- 🎯 **Smooth Scrolling** - Elegant navigation between sections

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Vanilla JS for interactivity
- **Google Fonts** - Orbitron & Outfit typography
- **Vercel** - Deployment platform

## 📂 Project Structure

```
techxhub-landing-page/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git installed on your machine
- (Optional) Node.js for local development server

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/techxhub-landing-page.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd techxhub-landing-page
   ```

3. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

4. **View the site**
   - Open `http://localhost:8000` in your browser

## 💻 Usage

### Shopping Cart
- Click "Add to Cart" on any product
- Click the cart icon in the navigation to view your cart
- Adjust quantities with +/- buttons
- Remove items with the trash icon
- View real-time total price

### Navigation
- Click navigation links for smooth scroll to sections
- Mobile-friendly navigation
- Sticky header stays visible while scrolling

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary: #2563eb;
    --secondary: #3b82f6;
    --accent: #1d4ed8;
}
```

### Products
Edit product data in `index.html` and update the `productIcons` object in `script.js`:
```javascript
const productIcons = {
    'Product Name': '🎧',
    // Add more products...
};
```

### Fonts
Change fonts by updating the Google Fonts import in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

## 📱 Responsive Design

The landing page is fully responsive with breakpoints at:
- **Desktop:** > 768px
- **Tablet:** 768px
- **Mobile:** < 768px

## 🌐 Deployment

### Deploy to Vercel

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel --prod
   ```

### Deploy to Netlify

1. Drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository

### Deploy to GitHub Pages

1. Go to repository Settings → Pages
2. Select branch (main) and folder (root)
3. Save and wait for deployment

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Chimdinma Melikam**

- Portfolio: [chimdinmamelikam.vercel.app](https://chimdinmamelikam.vercel.app)
- GitHub: [My GitHub](https://github.com/chimdinmamelikam)
- LinkedIn: [My LinkedIn](https://linkedin.com/in/loismelikam)

## 🙏 Acknowledgments

- Icons: Emoji icons for product representation
- Fonts: Google Fonts (Orbitron & Outfit)
- Inspiration: Modern e-commerce design trends
- Deployment: Vercel for seamless hosting

## 📸 Screenshots

### Desktop View
![Desktop View](./screenshots/desktop.png)

### Shopping Cart
![Shopping Cart](./screenshots/cart.png)

### Mobile View
![Mobile View](./screenshots/mobile.png)

## 🔮 Future Enhancements

- [ ] Backend integration with Node.js/Express
- [ ] Database for product management (MongoDB/PostgreSQL)
- [ ] User authentication and accounts
- [ ] Payment gateway integration (Stripe/PayPal)
- [ ] Product search and filtering
- [ ] Wishlist functionality
- [ ] Order tracking system
- [ ] Admin dashboard
- [ ] Email notifications
- [ ] Product reviews and ratings

## 📞 Contact

For questions or feedback, please reach out through the contact form on the website or open an issue in this repository.

---

⭐ **If you found this project helpful, please give it a star!** ⭐

Made with ❤️ by Chimdinma Melikam
