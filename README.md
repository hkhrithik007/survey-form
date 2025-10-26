Here's a comprehensive README for your Survey Form project:

---

# Responsive Survey Form

A lightweight, mobile-first survey form built with vanilla HTML, CSS, and JavaScript. Features client-side validation, accessible design, and error handling without any external dependencies.

## 🌟 Features

- **Fully Responsive**: Mobile-first design that adapts seamlessly to all screen sizes
- **Client-Side Validation**: Real-time field validation with helpful error messages
- **Accessibility First**: Proper ARIA labels and full keyboard navigation support
- **Zero Dependencies**: Pure vanilla JavaScript - no libraries or frameworks needed
- **Error States**: Visual feedback for invalid inputs with clear error messaging
- **Clean UI**: Modern, minimalist design with smooth animations

## 🚀 Demo

[Live Demo](#) <!-- Add your demo link here -->

## 📸 Screenshots

<!-- Add screenshots here -->

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for better accessibility
- **CSS3**: Modern styling with flexbox/grid layouts
- **Vanilla JavaScript**: Pure JS for form validation and interactivity

## 📋 Form Fields

The survey form includes:
- Text inputs with pattern validation
- Email validation
- Number inputs with min/max constraints
- Radio buttons for single-choice questions
- Checkboxes for multiple selections
- Dropdown menus
- Textarea for long-form responses

## 🎯 Validation Features

- Required field validation
- Email format validation
- Minimum/maximum length checks
- Pattern matching for specific formats
- Real-time error display
- Form submission prevention on invalid data

## 💻 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/hkhrithik007/survey-form.git
   cd survey-form
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   ```

3. **Or use a local server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

## 📁 Project Structure

```
survey-form/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript validation logic
└── README.md           # Project documentation
```

## 🎨 Customization

### Styling
Modify `styles.css` to customize:
- Color scheme
- Typography
- Spacing and layout
- Animation effects

### Validation Rules
Edit `script.js` to adjust:
- Validation patterns
- Error messages
- Custom validation logic

## ✨ Key Highlights

- **Lightweight**: Less than 50KB total size
- **Fast Loading**: No external dependencies means quick load times
- **Cross-Browser Compatible**: Works on all modern browsers
- **SEO Friendly**: Semantic HTML structure
- **Easy to Customize**: Clean, well-commented code

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Form Validation Example

```javascript
// Example validation function
function validateEmail(email) {
  const pattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
  return pattern.test(email);
}

// Real-time validation
emailInput.addEventListener('input', function() {
  if (!validateEmail(this.value)) {
    showError(this, 'Please enter a valid email address');
  } else {
    clearError(this);
  }
});
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Hritik Sharma**
- Email: hkhrithik083@gmail.com
- LinkedIn: [hritik-sharma-b554121b8](https://linkedin.com/in/hritik-sharma-b554121b8)
- GitHub: [@hkhrithik007](https://github.com/hkhrithik007)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built as part of web development practice
- Inspired by modern form design patterns
- Focus on accessibility and user experience

---

**⭐ If you found this project helpful, please consider giving it a star!**

---
