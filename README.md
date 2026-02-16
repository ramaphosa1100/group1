# 📦 InvyTrackInventory Management System

## Project Overview

InvyTrack is a comprehensive inventory management system designed to help businesses track, manage, and organize their products efficiently. The system provides an intuitive interface for viewing categories, managing products, adding new items, and handling contact inquiries.

## Features

### 📱 Responsive Design
- **Desktop View**: Traditional top navigation bar with hover effects
- **Mobile View**: Bottom fixed navigation bar (LinkedIn-style) for easy thumb access
- Fully responsive layout that adapts to all screen sizes

### 🗂️ Pages

#### 1. **Home Page** (`index.html`)
- Hero section with welcome message
- Rollover image gallery showcasing dashboard previews
- Key features overview table
- External resources links

#### 2. **Categories Page** (`categories.html`)
- Category statistics dashboard
- Visual category cards with:
  - Category images
  - Item counts
  - Total value
  - Low stock indicators
  - Category badges
- 8 main categories: Electronics, Clothing, Food & Beverages, Fitness, Stationery, Automobile, Accessories, Books

#### 3. **Products Page** (`products.html`)
- Advanced filtering options (by category, status, search)
- Product statistics summary
- Comprehensive product table with:
  - Product IDs
  - Icons for visual identification
  - Stock quantities
  - Pricing
  - Status indicators (In Stock, Low Stock, Out of Stock)
  - Action icons for editing
- Pagination for large inventories
- Sample products note showing 24 items out of 1,247 total

#### 4. **Add Item Page** (`add-item.html`)
- Comprehensive form for adding new products
- Form elements include:
  - Product name (text field)
  - **Category dropdown** with 8 options
  - Description (textarea)
  - Product type (radio buttons: Physical/Digital/Service)
  - Features (checkboxes: Warranty, Free Shipping, Bulk Discount)
  - Price and quantity (number inputs)
  - Condition dropdown (New/Refurbished/Used)
  - Image upload with preview box
  - Submit and Reset buttons

#### 5. **Contact Page** (`contact.html`)
- Contact information display
- Contact form with:
  - Name, email, subject fields
  - Message textarea
  - Inquiry type (radio buttons)
  - Newsletter and callback options (checkboxes)
- Quick links section
- Social media links

### 🎨 Design Features

#### Navigation
- **Desktop**: Top navigation with transparent hover effects (scales to 1.1x)
- **Mobile**: Bottom fixed navigation with active state highlighting
- Active page indicators for better user orientation

#### Interactive Elements
- Smooth transitions (0.3s ease) on all interactive elements
- Hover effects on:
  - Navigation items (scale + background)
  - Category cards (scale + shadow)
  - Table rows (background highlight)
  - Buttons (scale + shadow)
  - Icons (rotate + scale)
  - Social media links
- Click effects (scale down to 0.95x)

#### Visual Design
- Color scheme:
  - Primary gradient: `linear-gradient(135deg, #2c3e50, #4c6692)`
  - Accent color: `#4CAF50` (green)
  - Background: `#473d3d`
- Consistent card-based layout
- Status indicators with color coding:
  - 🟢 In Stock: Green
  - 🟡 Low Stock: Yellow
  - 🔴 Out of Stock: Red
- Font Awesome icons throughout

### 📊 Data Structure

#### Categories
```
- Electronics (245 items, $45,200 value)
- Clothing (312 items, $12,800 value)
- Food & Beverages (189 items, $5,450 value)
- Fitness (156 items, $8,900 value)
- Stationery (278 items, $3,800 value)
- Automobile (45 items, $52,000 value)
- Accessories (198 items, $6,750 value)
- Books (324 items, $6,800 value)
```

#### Sample Products
24 representative products across all categories with realistic pricing and stock levels.

## Technical Specifications

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Styling and animations
- **Font Awesome 6.5.0**: Icons and visual elements
- **Responsive Design**: Media queries for mobile/tablet/desktop

### CSS Features
- Flexbox and Grid layouts
- CSS transitions and transforms
- Gradient backgrounds
- Box shadows for depth
- Custom dropdown styling
- Responsive breakpoints:
  - Mobile: up to 767px
  - Tablet: 768px - 1024px
  - Desktop: 768px and above

### File Structure
```
project/
│
├── index.html          # Home page
├── categories.html     # Categories overview
├── products.html       # Product inventory
├── add-item.html       # Add new item form
├── contact.html        # Contact page
├── style.css          # Main stylesheet
│
├── images/            # Image directory
│   ├── dashboard.jpeg
│   ├── dashboard2.jpeg
│   ├── dashboard3.jpeg
│   ├── electronics.jpg
│   ├── clothing.jpg
│   ├── food.jpg
│   ├── fitness.jpg
│   ├── stationery.jpg
│   ├── automobile.jpg
│   ├── accessories.jpg
│   ├── books.jpg
│   └── placeholder.png
│
└── README.md          # Project documentation
```

## Installation & Setup

1. **Clone or download** the project files
2. **Ensure all images** are placed in the `/images` directory
3. **Open any HTML file** in a modern web browser
4. **No server required** - pure HTML/CSS static site

### Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Usage Guide

### Desktop Navigation
- Use the top navigation bar to switch between pages
- Hover over items for visual feedback
- Active page is highlighted

### Mobile Navigation
- Fixed bottom navigation for easy access
- Icons with labels for each section
- Home icon is slightly larger and highlighted

### Managing Products
1. **View Products**: Navigate to Products page
2. **Add New Item**: Go to Add Item page and fill the form
3. **Filter Products**: Use dropdown filters on Products page
4. **Check Status**: Color-coded indicators show stock levels

### Categories
- Click on category cards to view related products (functionality to be implemented)
- View statistics for each category

## Future Enhancements

Potential features to add:
- [ ] Backend integration (PHP/Node.js)
- [ ] Database connection (MySQL/MongoDB)
- [ ] User authentication system
- [ ] Real-time stock updates
- [ ] Search functionality
- [ ] Sort by column on products table
- [ ] Export data to CSV/Excel
- [ ] Print inventory reports
- [ ] Barcode scanning integration
- [ ] Email notifications for low stock
- [ ] Sales and purchase history
- [ ] Multi-user support with roles

## Credits

- **Developer**: Cyril Morti
- **Icons**: [Font Awesome](https://fontawesome.com)
- **Fonts**: Google Fonts (Segoe UI)

## License

© 2026 InvyTrack Inventory Management. All rights reserved.

---

**Note**: This is a front-end demonstration project. Form submissions and database functionality require backend implementation.
