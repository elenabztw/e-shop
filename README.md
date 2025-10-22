# 🎧 E-Shop - Electronics & Gadgets Store

A modern, responsive e-commerce website for electronics, gadgets, and accessories built with HTML5, CSS3, and Bootstrap 5.

E-Shop Preview
<img width="1480" height="1136" alt="image" src="https://github.com/user-attachments/assets/f87a408f-1788-4584-9e3b-43dd3b2c8240" />

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Pages](#pages)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Bootstrap 5 Framework** - Utilizes the latest Bootstrap components and grid system
- **CSS3 Animations** - Engaging hover effects and transitions
- **Semantic HTML5** - Proper markup for better SEO and accessibility
- **Video Main Section** - Eye-catching landing page with background video
- **Product Categories** - Organized product pages for different gadget types
- **Service Center Form** - Contact form for customer support and repairs
- **Bootstrap Icons** - Modern icon set for better visual communication
- **Smooth Scrolling** - Enhanced navigation experience
- **Sticky Navigation** - Fixed header that stays visible while scrolling

## 🚀 Demo

[Live Demo](#) *(https://electronicsshopsite.netlify.app/)*

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties (variables)
- **Bootstrap 5.3.0** - Responsive framework
- **Bootstrap Icons 1.10.0** - Icon library
- **Google Fonts** - Open Sans Condensed & Raleway typography

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, Atom, etc.)
- Basic knowledge of HTML, CSS, and Bootstrap

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/e-shop.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd e-shop
   ```

3. **Add your video file**
   - Place your `Video.mp4` file in the root directory
   - Or update the video source in `index.html`

4. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js http-server
   npx http-server
   ```

5. **View the website**
   - Navigate to `http://localhost:8000` (or appropriate port)

## Project Structure

```
e-shop/
│
├── index.html                      # Main homepage
├── style.css                       # Custom CSS styles
├── Аксессуарыдлятел.html          # Phone accessories page
├── Девайсы.html                    # Devices page
├── Дляздоровья.html               # Health gadgets page
├── Длядома.html                    # Home gadgets page
├── сервис.html                     # Service center page
├── Video.mp4                       # Main section background video
├── humidifier.jpg                  # Product image (optional)
└── README.md                       # Project documentation
```

## Pages

### Home Page (`index.html`)
- Main section with video background
- Product categories overview
- Warranty information
- Contact section

### Product Pages
- **Аксессуарыдлятел.html** - Phone accessories (AirPods, cases, holders)
- **Девайсы.html** - Devices (smartwatches, headphones, cameras)
- **Дляздоровья.html** - Health gadgets (blenders, scales, fitness accessories)
- **Длядома.html** - Home gadgets (security cameras, thermometers, humidifiers)

### Service Page (`сервис.html`)
- Customer support form
- Product repair request form
- Contact information

## Customization

### Colors

The website uses CSS custom properties for easy color customization. Edit these in `style.css`:

```css
:root {
    --primary-color: #ecb390;      /* Main brand color */
    --secondary-color: #fcf8e8;    /* Light background */
    --text-dark: #404b69;          /* Dark text */
    --text-light: #283149;         /* Body text */
    --accent-color: #df7861;       /* Accent/price color */
    --success-color: #0d8bc5;      /* Links/hover color */
    --bg-light: #d4e2d4;           /* Page background */
}
```

### Fonts

Change fonts by modifying the Google Fonts import in the HTML `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

Then update the CSS:

```css
body {
    font-family: 'YourFont', sans-serif;
}
```

### Content

- **Text**: Edit HTML files directly to change product names, descriptions, and prices
- **Images**: Replace image URLs or add local images
- **Video**: Replace `Video.mp4` with your own video file
- **Contact Info**: Update email addresses and phone numbers in all pages

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## To-Do / Future Enhancements

- [ ] Add shopping cart functionality
- [ ] Implement product search feature
- [ ] Create product detail pages
- [ ] Add user authentication
- [ ] Integrate payment gateway
- [ ] Add product reviews and ratings
- [ ] Implement wishlist feature
- [ ] Add multi-language support
- [ ] Create admin dashboard
- [ ] Add newsletter subscription

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Bootstrap](https://getbootstrap.com/) - Frontend framework
- [Bootstrap Icons](https://icons.getbootstrap.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Typography
- [Unsplash](https://unsplash.com/) - Stock images

---
Elena B

⭐ **If you like this project, please give it a star!** ⭐

Made with ❤️ by E-Shop Team
