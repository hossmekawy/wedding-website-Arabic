# 💍 Elegant Arabic Wedding Invitation System

<div align="center">
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge" alt="Status: Live">
  <img src="https://img.shields.io/badge/Language-HTML/CSS/JS-orange?style=for-the-badge" alt="Language: HTML/CSS/JS">
  <img src="https://img.shields.io/badge/Framework-TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Framework: TailwindCSS">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License: MIT">
</div>

<p align="center">
  <img src="https://i.pinimg.com/736x/55/f2/9b/55f29b595dbc0274ed369abc2dbbb218.jpg" alt="Wedding Invitation Preview" width="300">
</p>

## ✨ Live Demo

Experience the elegance:  
**[View Live Wedding Invitation](https://charming-gnome-026471.netlify.app/)**

## 🌟 Features

- 🌙 Beautiful Arabic typography and RTL layout
- 📱 Fully responsive, mobile-first design
- 🎨 Elegant color scheme with subtle animations
- 📅 Live countdown to the wedding date
- 📝 RSVP functionality with form validation
- 📍 Google Maps integration for venue location
- 📱 Personalized QR code generation
- 🖼️ Downloadable personalized invitation

## 💻 Technologies

- HTML5, CSS3, JavaScript
- TailwindCSS for styling
- Intersection Observer API for scroll animations
- Canvas API for downloadable invitations
- Google Fonts for Arabic typography
- Font Awesome for icons

## 📋 Implementation Details

The wedding invitation system features:

```javascript
// Personalized QR code generation
function generatePersonalizedQR(name) {
  const message = `انت مدعو للفرح يا ${name}`;
  return `https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=${encodeURIComponent(message)}&bgcolor=F8F6F0&color=D8B4B4`;
}

// Countdown timer implementation
function updateCountdown() {
  const weddingDate = new Date('February 10, 2025 18:00:00').getTime();
  const now = new Date().getTime();
  const distance = weddingDate - now;
  
  // Calculate days, hours, minutes, seconds...
  
  // Update UI with countdown values
}
```

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/hossmekawy/wedding-website-Arabic.git
   ```

2. Open `index.html` in your browser or deploy to your favorite hosting service

3. Customize the invitation details in the HTML file

## 🎨 Customization

You can easily customize:
- Couple names and photos
- Wedding date and venue
- Color scheme (via TailwindCSS config)
- Messages and Quranic verses
- Parents' names

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

<div align="center">
  <a href="https://github.com/hossmekawy">
    <img src="https://img.shields.io/badge/GitHub-hossmekawy-181717?style=for-the-badge&logo=github" alt="GitHub: hossmekawy">
  </a>
</div>

<p align="center">
  Made with ❤️ by Hussein El Mekawy
</p>
