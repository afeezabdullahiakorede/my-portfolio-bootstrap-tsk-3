# Afeez Abdullahi Akorede - Portfolio Website

A modern, responsive portfolio website showcasing web development skills and projects. Built with **HTML5**, **CSS3**, and **Bootstrap 5** for a seamless user experience across all devices.

## 🌟 Features

- **Responsive Design**: Mobile-first approach ensures the layout remains fluid across all screen sizes
- **Modern Navigation**: Collapsible navbar with smooth navigation links
- **Hero Section**: Engaging welcome section with call-to-action button
- **Portfolio Display**: Project showcase with visual and descriptive layouts
- **Skills Section**: Grid-based display of technical skills with icons
- **Back to Top Button**: Floating button that appears after scrolling 300px down, with smooth scroll animation
- **Dark Mode Toggle**: Switch between light and dark themes with persistent storage using localStorage
- **Image Hover Effects**: Smooth zoom animation on portfolio images for enhanced interactivity
- **Contact Form**: Functional contact form with Formspree integration for message submission
- **Clean UI**: Bootstrap 5 components for professional appearance
- **Accessibility**: Semantic HTML and proper meta tags for better accessibility

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, responsive layouts, and dark mode themes
- **JavaScript**: Interactive features (scroll detection, smooth scrolling, dark mode toggle, localStorage integration)
- **Bootstrap 5.3.3**: Responsive framework and pre-built components
- **Bootstrap Icons**: Icon library for visual enhancement
- **Formspree**: Backend form handling service for contact form submissions
- **CDN-based**: No build process required; just open and use
- **LocalStorage API**: Persistent theme preference across sessions

## 🌙 Dark Mode Feature

The portfolio includes a fully functional dark mode toggle that enhances user experience:

- **One-Click Toggle**: Easy-to-use button to switch between light and dark themes
- **Persistent Storage**: Theme preference is saved in localStorage and persists across browser sessions
- **Custom Colors**: Dark mode uses high-contrast colors (black background, white text, yellow accents) for optimal readability
- **Smooth Transitions**: CSS transitions ensure smooth theme switching without jarring color changes
- **Bootstrap Integration**: Leverages Bootstrap's theming system with `data-bs-theme` attribute

**How it works:**
1. User clicks the dark mode toggle button
2. JavaScript detects the change and updates the `data-bs-theme` attribute on the HTML element
3. Theme preference is saved to localStorage
4. On page reload, the saved theme is automatically applied

## 📁 Project Structure

```
CODVEDA-TSK-2-LV-2/
├── index.html       # Main portfolio page with all features
└── README.md        # Project documentation
```

**Note:** The contact form integrates with Formspree for backend processing. Form submissions are handled externally and don't require additional server-side files in this project.

## 📧 Contact Form Feature

The portfolio includes a fully functional contact form powered by Formspree:

- **Formspree Integration**: Serverless form handling without backend setup
- **Required Validation**: All fields (name, email, message) are required for submission
- **Email Notifications**: Form submissions are sent directly to your email
- **Redirect on Success**: Users are redirected to a thank you page after successful submission
- **Spam Protection**: Honeypot field and built-in spam filtering
- **Responsive Design**: Form adapts perfectly to all screen sizes

**Form Fields:**
- **Name**: Text input for visitor's full name
- **Email**: Email input with validation
- **Message**: Multi-line textarea for detailed messages

**How it works:**
1. User fills out the contact form with their details
2. Formspree processes the submission server-side
3. Email notification is sent to your inbox
4. User is redirected to a thank you page
5. Form data is securely stored and managed by Formspree

**Setup Requirements:**
- Active Formspree account (free tier available)
- Form endpoint URL (already configured: `https://formspree.io/f/xrejvolq`)
- Thank you page URL for post-submission redirect

## 👤 Author

**Afeez Abdullahi Akorede**
- Front-End Developer
- Specialized in responsive, user-friendly web experiences

---

**Last Updated**: May 14, 2026

