# Accessible Form UI

A modern, accessible user profile form with interactive elements and real-time validation feedback. This project demonstrates best practices for web accessibility and form design.

🔗 **Project Challenge**: [roadmap.sh/projects/accessible-form-ui](https://roadmap.sh/projects/accessible-form-ui)

## ✨ Features

- **Fully Accessible**: WCAG 2.1 compliant with proper ARIA attributes
- **Password Toggle**: Show/hide password functionality with keyboard support
- **Form Validation**: Real-time validation with error states and feedback
- **Progress Tracking**: Visual progress indicator with completion checklist
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Screen Reader Friendly**: Comprehensive support for assistive technologies

## 🎯 Accessibility Features

- ✅ Proper semantic HTML structure
- ✅ ARIA attributes for enhanced screen reader support
- ✅ Keyboard navigation support
- ✅ Focus management and visual indicators
- ✅ Error announcements with `aria-live` regions
- ✅ High contrast mode support
- ✅ Reduced motion preferences respected

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Accessible-Form-UI
   ```

2. Open `index.html` in your browser or serve it with a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .
   ```

3. Navigate to `http://localhost:8000` to view the form

## 📁 Project Structure

```
Accessible-Form-UI/
├── index.html          # Main HTML structure
├── style.css           # Styles and accessibility enhancements
└── README.md           # Project documentation
```

## 🎨 Design

The form features a clean, modern design with:
- Two-column layout (form + progress tracker)
- Rounded container with subtle shadows
- Error states with visual and textual feedback
- Interactive password visibility toggle
- Progress circle showing completion percentage
- Checklist with completed/pending task indicators

## 🧪 Testing Accessibility

Test the form with:
- **Keyboard navigation**: Tab through all interactive elements
- **Screen readers**: NVDA, JAWS, or VoiceOver
- **High contrast mode**: Windows High Contrast or browser extensions
- **Color blindness**: Ensure information isn't conveyed by color alone

## 📱 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
