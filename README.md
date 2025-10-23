# Smart Watch E-commerce Landing Page

A modern, responsive landing page for a smart watch e-commerce website built with HTML, CSS, and Tailwind CSS.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI**: Clean and modern design with a dark theme and professional styling
- **Brand Showcase**: Features popular smart watch brands including Apple, Xiaomi, and FitBit
- **Product Catalog**: Displays latest smart watch products with pricing and ratings
- **Customer Reviews**: Testimonials section showcasing customer satisfaction
- **Newsletter Subscription**: Email subscription form for marketing campaigns
- **Search Functionality**: Product search feature in the hero section

## 🎨 Design System

### Color Palette
- **Primary**: `#1E1D1D` (Dark background)
- **Secondary Light**: `#8B8E99` (Gray text)
- **Light Background**: `#F6F6F6` (Card backgrounds)
- **Accent Blue**: `#3858D6` (Buttons and highlights)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Font Weights**: 100-900 (variable font)

## 📁 Project Structure

```
watch-website-asset/
├── css/
│   └── style.css          # Custom CSS styles
├── images/               # All project images
│   ├── logo.png          # Website logo
│   ├── apple.png         # Apple brand logo
│   ├── xiaomi.png        # Xiaomi brand logo
│   ├── fitbit.png        # FitBit brand logo
│   ├── product1-6.png    # Product images
│   ├── people1-2.png     # Customer testimonial images
│   └── ...               # Other UI icons and images
├── deesign/
│   ├── readme            # Design specifications
│   └── template.png      # Design template
├── index.html            # Main HTML file
├── tailwind.config.js    # Tailwind CSS configuration
└── README.md            # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling and animations
- **Tailwind CSS**: Utility-first CSS framework
- **Google Fonts**: Inter font family
- **Responsive Design**: Mobile-first approach

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- No additional dependencies required (uses CDN for Tailwind CSS)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd watch-website-asset
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View the website**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or open `index.html` directly in your browser

## 📱 Sections Overview

### 1. Header & Navigation
- Logo and brand name
- Navigation menu (Home, Brands, Recent Products, Contact, About)
- Search, user account, and shopping cart icons

### 2. Hero Section
- Compelling headline: "Discover Most Suitable Watches"
- Search functionality for finding brands
- Hero image showcasing smart watches

### 3. Brand Showcase
- Featured brands: Apple, Xiaomi, and FitBit
- Brand descriptions and logos
- Grid layout for easy browsing

### 4. Product Catalog
- Latest smart watch products
- Product images, names, and pricing
- Star ratings for each product
- "View More" call-to-action button

### 5. Customer Testimonials
- Customer reviews and ratings
- Customer photos and names
- Social proof for the brand

### 6. Newsletter Subscription
- Email subscription form
- Marketing copy and compelling imagery
- Call-to-action for newsletter signup

### 7. Footer
- Copyright information
- Brand attribution

## 🎯 Key Features Implementation

### Responsive Grid System
- Uses Tailwind CSS grid classes
- Responsive breakpoints: `sm:`, `md:`, `lg:`
- Mobile-first design approach

### Interactive Elements
- Hover effects on buttons and links
- Form validation ready
- Search functionality placeholder

### Performance Optimizations
- Optimized images
- CDN-based Tailwind CSS
- Minimal custom CSS

## 🔧 Customization

### Colors
To change the color scheme, update the CSS custom properties in `css/style.css` or modify Tailwind classes in `index.html`.

### Content
- Update product information in the product catalog section
- Modify brand descriptions in the brand showcase
- Change customer testimonials in the reviews section

### Images
Replace images in the `images/` folder with your own:
- Maintain aspect ratios for consistent layout
- Use optimized formats (WebP, PNG, JPG)
- Ensure images are responsive-friendly

## 📄 License

This project is part of a coding challenge and is for educational/demonstration purposes.

## 🤝 Contributing

This is a coding challenge project. If you'd like to suggest improvements or report issues, please feel free to create an issue or submit a pull request.

## 👨‍💻 Author

**Fathima Jufla**
- GitHub: [@fathimajufla](https://github.com/fathimajufla)
- Project: Smart Watch E-commerce Landing Page
- Created as part of a coding challenge

## 📞 Contact

For questions about this project, please refer to the project documentation or contact the development team.

---

**Note**: This is a static website template. For a production e-commerce site, you would need to integrate with a backend system for user authentication, payment processing, and inventory management.
