# E-Plant Shopping 🌿🛒

A modern, responsive e-commerce web application for buying plants online. Built with HTML, CSS, and JavaScript, this project demonstrates front-end development skills including dynamic product management, shopping cart functionality, and local storage integration. Perfect for plant enthusiasts looking to browse and purchase plants from home.

## 🚀 Features

### Product Management
- **Browse Plants**: Explore a wide variety of plants with detailed descriptions and prices.
- **Product Categories**: Organized categories for easy navigation.
- **Product Details**: View comprehensive information about each plant including care instructions and pricing.
- **Image Gallery**: High-quality plant images for better visualization.

### Shopping Cart
- **Add to Cart**: Easily add plants to your shopping cart.
- **Modify Quantities**: Adjust item quantities directly in the cart.
- **Remove Items**: Delete unwanted items from your cart.
- **Cart Persistence**: Your cart data is saved using local storage.
- **Real-time Updates**: Instant cart total calculation and item count.

### User Experience
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices.
- **User-Friendly Interface**: Intuitive navigation and clear product information.
- **Search Functionality**: Find plants quickly by name or characteristics.
- **Checkout Summary**: Review your order before purchase.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: CSS3 (Flexbox & Grid)
- **Storage**: Browser Local Storage API
- **Version Control**: Git & GitHub

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MarekBProgrammer/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Open the application**
   Simply open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **Access the application**
   Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## ▶️ Usage

1. **Browse Plants**: Navigate through the product catalog.
2. **View Details**: Click on a plant to see full information and pricing.
3. **Add to Cart**: Click the "Add to Cart" button to purchase items.
4. **Manage Cart**: Open the shopping cart to:
   - Increase/decrease quantities
   - Remove items
   - View total price
5. **Checkout**: Review your order and proceed with purchase.

## 📂 Project Structure

```
e-plantShopping/
├── index.html              # Main HTML file
├── styles.css              # Main stylesheet
├── script.js               # JavaScript logic
├── assets/
│   ├── images/            # Product images
│   ├── icons/             # UI icons
│   └── logo.png           # Brand logo
├── data/
│   └── plants.json        # Product database (or inline in JS)
└── README.md              # This file
```

## 💾 Local Storage

The application uses browser Local Storage to persist user data:
- **Shopping Cart**: Items, quantities, and prices
- **User Preferences**: Selected filters and sorting options
- **Wishlist**: (Optional feature) Saved favorite plants

Data is automatically saved when you add/remove items and persists across browser sessions.

## 🎨 Features in Detail

### Product Catalog
- Dynamically generated product cards
- Price display with currency formatting
- Stock availability indicators
- Plant care level badges (Beginner, Intermediate, Expert)

### Shopping Cart System
- Real-time cart count in header
- Subtotal and total price calculations
- Remove and quantity adjustment buttons
- Empty cart message when no items

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Technologies Explained

### HTML5
- Semantic markup for better SEO and accessibility
- Forms for user input
- Product listing structure

### CSS3
- Flexbox for layouts
- Grid for product grids
- Media queries for responsiveness
- CSS animations for smooth interactions
- CSS variables for maintainable theming

### JavaScript (Vanilla)
- DOM manipulation
- Event listeners (click, change, input)
- Local Storage API
- Array methods (map, filter, reduce)
- ES6+ features (arrow functions, template literals, destructuring)

## 📊 Sample Data Structure

```javascript
{
  id: 1,
  name: "Monstera Deliciosa",
  price: 45.99,
  image: "monstera.jpg",
  category: "Indoor Plants",
  careLevel: "Beginner",
  description: "Popular Swiss Cheese Plant with large split leaves",
  inStock: true,
  quantity: 5
}
```

## 🎯 Learning Outcomes

This project demonstrates:
- Building responsive web layouts with CSS3
- DOM manipulation with vanilla JavaScript
- Local Storage API for data persistence
- Event handling and user interactions
- Creating dynamic product listings
- Implementing shopping cart functionality
- State management without frameworks
- Git version control and GitHub collaboration

## 🚀 Future Enhancements

Potential features for expansion:
- Backend API integration
- User authentication system
- Payment gateway integration
- Product reviews and ratings
- Wishlist functionality
- Order history
- Admin dashboard for inventory management
- Email confirmation system
- Advanced search and filtering

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Best Practices Implemented

- Semantic HTML structure
- CSS organization and naming conventions
- JavaScript modularization
- Local Storage error handling
- Responsive mobile-first design
- Performance optimization
- Cross-browser compatibility

## 👤 Author

**MarekBProgrammer**
- GitHub: [@MarekBProgrammer](https://github.com/MarekBProgrammer)
- Repository: [e-plantShopping](https://github.com/MarekBProgrammer/e-plantShopping)

## 📄 License

This project is part of front-end web development learning and practice.

---

**Happy shopping! 🌱** If you have questions or suggestions, feel free to open an issue on GitHub.
