# ☕ Caffeine Cove - Coffee Shop Website

A modern, responsive website for Caffeine Cove, a premium coffee shop dedicated to quality, sustainability, and customer experience.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Sections](#sections)
- [Technologies Used](#technologies-used)
- [Responsive Design](#responsive-design)
- [Credits](#credits)

## 🎯 About

Caffeine Cove is a cozy neighborhood café that combines passion for great coffee with a welcoming atmosphere. This website showcases the café's menu, values, and provides customers with an easy way to make reservations.

## ✨ Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Navigation**: Smooth scrolling navigation with fixed header
- **Menu Showcase**: 8 premium coffee and beverage options with descriptions and pricing
- **Customer Testimonials**: Real customer reviews and experiences
- **Reservation System**: Booking form with date, time, and party size selection
- **Location Integration**: Embedded Google Map showing café location
- **Social Media Links**: Direct connections to Facebook, Instagram, Telegram, Behance, and GitHub
- **Modern UI/UX**: Clean design with hover effects and smooth transitions

## 📁 Project Structure

```
caffeine-cove/
├── index.html          # Main HTML file with all sections
├── style.css           # Complete styling and responsive design
├── imgs/               # Image assets directory
│   ├── favicon.ico
│   ├── logo.png
│   ├── home-bg.png
│   ├── coffee-home.png
│   ├── about-img.png
│   ├── menu-1.png to menu-8.png
│   ├── person1.jpg to person3.jpg
│   ├── footer-bg.png
│   └── home-bg.png
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side setup required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ahmedattay/caffeine-cove.git
```

2. Navigate to the project directory:
```bash
cd caffeine-cove
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

4. Visit `http://localhost:8000` in your browser

## 📑 Sections

### 1. **Home**
Hero section featuring the café's tagline, brief description, and call-to-action button linked to an external coffee supplier.

### 2. **About**
Information about Caffeine Cove's history, cozy atmosphere, commitment to quality, and sustainable sourcing practices.

### 3. **Menu**
Display of 8 popular beverages:
- Espresso
- Caramel Vanilla Latte
- Hot Chocolate
- Turkish Coffee
- Brazilian Coffee
- Black Coffee
- Nescafe

Each item includes description and pricing in Egyptian Pounds (E£).

### 4. **Testimonials**
Three customer reviews highlighting the café's quality, ambiance, and service.

### 5. **Reservation**
Contact form allowing customers to:
- Enter their name and email
- Specify party size
- Select date and time
- Add special requests
- Embedded map showing café location in Haram, Giza

### 6. **Footer**
- About information with contact details
- Quick navigation links
- Social media icons and links
- Copyright information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and form elements
- **CSS3**: Modern styling with CSS Variables and Grid/Flexbox layouts
- **Google Fonts**: Open Sans and Oswald typography
- **Font Awesome**: Icon library (v7.0.1)
- **Google Maps API**: Embedded location map
- **Responsive Design**: Mobile-first approach with media queries

## 📱 Responsive Design

The website is optimized for three main breakpoints:

- **Desktop** (1000px and above): Full multi-column layouts
- **Tablet** (600px - 1000px): Adjusted spacing and single-column menu
- **Mobile** (Below 600px): 
  - Stacked navigation
  - Single-column layout for all sections
  - Optimized touch targets
  - Readable font sizes
  - Mobile-friendly map height (300px)

### CSS Variables

The design uses CSS variables for easy customization:
```css
--bg-color: #f1f1f1;           /* Light gray background */
--bg-secondary: #fbfbfb;       /* Secondary light background */
--dark-gray: #333;             /* Dark gray for text */
--light-brown: #c7a17a;        /* Coffee/brown accent color */
--black: #1f2226;              /* Deep black */
```

## 🎨 Design Features

- Smooth scroll behavior across all sections
- Hover effects on navigation, menu items, and buttons
- Box shadows for depth and interactivity
- Scale animations on images and price elements
- Responsive images with proper aspect ratios
- Accessible color contrast ratios

## 📞 Contact Information

- **Location**: Haram, Giza, Egypt
- **Email**: ahmedattay8@gmail.com
- **Phone**: +20 1014911302

### Social Media
- [Facebook](https://www.facebook.com/profile.php?id=100017576253378)
- [Instagram](https://www.instagram.com/a9md26/)
- [Telegram](https://t.me/ahmedozdesign)
- [Behance](https://www.behance.net/ahmedattay_)
- [GitHub](https://github.com/Ahmedattay)

## 👨‍💻 Credits

**Project Based On**: Tutorial by [Mohamed Elkashef](https://www.youtube.com/@Mohamed.Elkashef)

**Developer**: [Ahmed Attay](https://www.linkedin.com/in/ahmed-attay-173888252/)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 🐛 Issues & Support

If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.

---

Made with ☕ and ❤️ by Ahmed Attay
