# Paradise Nursery Shopping Cart Application

A complete React shopping cart application for Paradise Nursery plant shop with Redux state management.

## 🌱 Project Overview

Paradise Nursery is a beautiful, responsive e-commerce application for purchasing house plants. The application features a comprehensive shopping cart system with Redux state management, allowing users to browse plants by categories, add items to cart, and manage their shopping experience.

## ✨ Features

### Core Functionality
- **Landing Page** - Welcome page with navigation to product listing
- **Product Listing** - Display plants organized by categories with images, descriptions, and pricing
- **Shopping Cart** - Full cart functionality with add, remove, and quantity management
- **Navigation** - Seamless navigation between landing, products, and cart pages
- **Real-time Updates** - Cart icon shows current item count, totals update dynamically

### Plant Categories
- **Air Purifying Plants** - Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera
- **Aromatic Fragrant Plants** - Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth
- **Insect Repellent Plants** - Oregano, Marigold, Geraniums, Basil, Lavender, Catnip
- **Medicinal Plants** - Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula
- **Low Maintenance Plants** - ZZ Plant, Pothos, Snake Plant, Cast Iron Plant, Succulents, Aglaonema

### Cart Operations
- **Add to Cart** - Add plants to shopping cart with visual feedback
- **Quantity Management** - Increase/decrease quantities with +/- buttons
- **Remove Items** - Delete individual items or reduce quantity to zero
- **Total Calculations** - Real-time calculation of item totals and cart total
- **Continue Shopping** - Return to product listing from cart
- **Checkout** - Placeholder for future payment integration

## 🛠 Technical Stack

- **Frontend Framework**: React 18
- **State Management**: Redux Toolkit
- **Build Tool**: Vite
- **Styling**: CSS with responsive design
- **Package Manager**: npm

## 📁 Project Structure

```
src/
├── App.jsx                 # Main application component
├── ProductList.jsx         # Product listing and navigation
├── CartItem.jsx           # Shopping cart component
├── CartSlice.jsx          # Redux slice for cart state
├── store.js               # Redux store configuration
├── main.jsx               # Application entry point
├── ProductList.css        # Styling for product components
├── CartItem.css          # Styling for cart components
└── index.css             # Global styles
```

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd e-plantShopping
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

## 🎯 Usage

1. **Landing Page**: Click "Get Started" to enter the application
2. **Browse Plants**: View plants organized by categories with detailed information
3. **Add to Cart**: Click "Add to Cart" on any plant (button becomes "Added to Cart")
4. **Manage Cart**: 
   - Click cart icon to view cart contents
   - Use +/- buttons to adjust quantities
   - Click "Delete" to remove items
   - View real-time total calculations
5. **Continue Shopping**: Return to product listing to add more items
6. **Checkout**: Placeholder for future payment processing

## 🔧 Redux State Management

### CartSlice Actions
- **addItem**: Add new item to cart or increment existing item quantity
- **removeItem**: Remove item completely from cart
- **updateQuantity**: Update specific item quantity

### State Structure
```javascript
{
  cart: {
    items: [
      {
        name: "Snake Plant",
        image: "image-url",
        cost: "$15",
        description: "Plant description",
        quantity: 2
      }
    ]
  }
}
```

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile devices

## 🎨 Design Features

- **Green Theme**: Consistent with plant/nature branding
- **Card Layout**: Clean product cards with hover effects
- **Visual Feedback**: Button states change when items are added
- **Sale Badges**: Eye-catching sale indicators on products
- **Professional Navigation**: Clean header with logo and cart icon

## 🧪 Testing

All functionality has been thoroughly tested:
- ✅ Product display and categorization
- ✅ Add to cart functionality
- ✅ Cart quantity management (increment/decrement)
- ✅ Item removal and deletion
- ✅ Total calculations (individual and cart total)
- ✅ Navigation between pages
- ✅ Real-time UI updates
- ✅ Responsive design
- ✅ Redux state management

## 🚀 Deployment

### GitHub Pages Deployment

1. **Build the application**
   ```bash
   npm run build
   ```

2. **Install gh-pages**
   ```bash
   npm install --save-dev gh-pages
   ```

3. **Add deployment scripts to package.json**
   ```json
   {
     "homepage": "https://yourusername.github.io/e-plantShopping",
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d dist"
     }
   }
   ```

4. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```

## 🔮 Future Enhancements

- **Payment Integration**: Complete checkout functionality
- **User Authentication**: User accounts and order history
- **Plant Search**: Search functionality across all plants
- **Plant Filters**: Filter by price, category, care level
- **Wishlist**: Save favorite plants for later
- **Plant Care Guide**: Detailed care instructions for each plant
- **Reviews & Ratings**: Customer reviews and plant ratings
- **Inventory Management**: Stock tracking and availability

## 👨‍💻 Development Notes

This project demonstrates:
- Modern React development with functional components and hooks
- Redux Toolkit for efficient state management
- Responsive CSS design principles
- Component composition and reusability
- Event handling and user interaction
- Real-time UI updates and state synchronization

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Paradise Nursery** - Where Green Meets Serenity 🌿

