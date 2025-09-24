# Food Delivery Website

A modern, responsive food delivery website built with HTML, CSS, and JavaScript. This project showcases a clean and user-friendly interface for ordering food online with features like menu browsing, cart functionality, and mobile responsiveness.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Navigation**: Collapsible mobile menu with smooth animations
- **Menu Grid**: Display of food items with images, descriptions, and prices
- **Shopping Cart**: Add items to cart with counter display
- **Hero Section**: Eye-catching landing area with call-to-action buttons
- **Social Media Integration**: Links to social media platforms
- **Contact Information**: Footer with contact details and quick links
- **Smooth Scrolling**: Enhanced user experience with smooth page navigation
- **Form Validation**: Basic form handling for user interactions

## 📁 Project Structure

```
food-delivery-web/
├── index.html          # Main HTML file
├── style.css           # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── images/             # Directory containing food images and assets
│   ├── burger.png
│   ├── pizza.png
│   ├── fried-chicken.png
│   ├── lasagna.png
│   ├── chicken-roll.png
│   ├── best-quality.png
│   ├── easy-to-order.png
│   ├── fast-delivery.png
│   ├── delivery-boy.png
│   └── ... (other images)
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Custom properties, Flexbox, Grid, and media queries for styling
- **JavaScript (ES6+)**: DOM manipulation and event handling
- **Font Awesome**: Icons for UI elements
- **Google Fonts**: Roboto Condensed font family

## 🚀 Setup and Installation

1. **Clone or Download**: Get the project files to your local machine
2. **No Installation Required**: This is a static website, no server setup needed
3. **Open in Browser**: Simply open `index.html` in any modern web browser

### Running Locally

1. Ensure all files are in the same directory
2. Open `index.html` in your preferred browser
3. For development, you can use a local server:
   ```bash
   # Using Python (if installed)
   python -m http.server 8000

   # Using Node.js (if installed)
   npx http-server

   # Then visit http://localhost:8000
   ```

## 🎯 Usage

1. **Navigation**: Use the header navigation to browse different sections
2. **Mobile Menu**: On mobile devices, click the hamburger menu to access navigation
3. **Menu Browsing**: Scroll to the "Our Menu" section to view available items
4. **Add to Cart**: Click on menu items to add them to your cart (demo functionality)
5. **Social Links**: Connect via social media icons in the hero section
6. **Contact**: Find contact information in the footer

## 🎨 Design Features

- **Color Scheme**: Warm yellows and golds with dark accents for a food-themed aesthetic
- **Typography**: Clean, readable Roboto Condensed font
- **Layout**: Flexbox and CSS Grid for responsive layouts
- **Animations**: Hover effects and smooth transitions
- **Icons**: Font Awesome icons for enhanced visual appeal

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with side-by-side hero content
- **Tablet**: Adjusted grid and spacing
- **Mobile (< 780px)**: Stacked layout, mobile menu, optimized typography

## 🔧 Customization

### Adding New Menu Items

1. Add image to `images/` directory
2. Update `index.html` in the menu section:
   ```html
   <div class="menu-item">
       <img src="images/your-image.png" alt="Item Name">
       <h3>Item Name</h3>
       <p class="price">$Price</p>
       <p class="description">Description here.</p>
   </div>
   ```

### Modifying Styles

- Edit `style.css` to change colors, fonts, or layouts
- Custom properties in `:root` make theme changes easy
- Media queries can be adjusted for different breakpoints

### Extending JavaScript

- Add new features in `script.js`
- Event listeners are already set up for cart and menu interactions

## 🐛 Known Issues / Limitations

- Cart functionality is demo-only (no backend persistence)
- Images are placeholder and may need optimization
- Form submission is simulated (no actual processing)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or support, please contact the development team or create an issue in the repository.

Author

**RIZWAN KHAN NASAR**

💼 LinkedIn: linkedin.com/in/rizwan-khan-nasar-35b147360

---

**Enjoy your food delivery experience! 🍕🍔🥗**
