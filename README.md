# Alpine Bliss Resort Website

A two-page website project built for educational purposes as part of a web development course.  
The site uses semantic HTML5, external CSS styling, accessible form elements, and matches the provided wireframes.

---

## 📖 Overview

The **Alpine Bliss Resort** website contains:

### 🏔 Home Page (`index.html`)
- Hero image: **Swiss Valley** scene
- Introductory section highlighting the resort’s amenities
- Two content groups with alternating image/text layouts:
  - **Swiss Chalet**
  - **Snowy Chalet**
- Clean, semantic HTML structure

### ✉ Contact Page (`contact.html`)
- Hero image: **Swiss Valley**
- Page intro text with required field notice
- Contact form:
  - Full name (required)
  - Email address (required)
  - Phone number (required)
  - Preferred contact method (email or phone, required)
  - Comments (required)
  - Submit button
- Form uses `POST` method with `https://wp.zybooks.com/form-viewer.php` as the action
- Side-by-side layout with **Swiss Peak** image
- Accessibility:
  - `aria-required` attributes on required fields
  - Descriptive `alt` text for images

---

## 🎨 Wireframes

- **Option 2** for both Home and Contact pages  
- Layouts strictly follow the provided wireframe designs, with enhancements for modern look and usability

---

## 🛠 Technologies

- **HTML5** for structure
- **CSS3** for styling
  - CSS variables for colors
  - All font sizes in `rem` units for scalability
- **Google Fonts**: *Lora* and *Open Sans*
- **Responsive Design**:
  - Fixed-width content (1280px) centered in the viewport
  - Flexible image sizing
- **Accessibility**: Semantic tags, ARIA attributes, alt text

---

## 📂 File Structure

```

project/
│
├── index.html              # Home page
├── contact.html            # Contact page
├── styles.css              # External stylesheet
│
├── images/
│   ├── favicon.png
│   ├── swiss-valley.jpg
│   ├── swiss-chalet.jpg
│   ├── snowy-chalet.jpg
│   ├── swiss-peak.jpg
│   └── swiss-sunset.jpg
│
└── README.md               # Documentation

````

---

## ✨ Features

- **Professional Layout** matching wireframes
- **Consistent Theme** across pages (colors, spacing, typography)
- **Visual Feedback**:
  - Navigation hover and active states
  - Form focus/invalid styling
  - Animated button hover
  - Hero image zoom-on-hover
- **Performance & Usability**:
  - `loading="lazy"` for non-critical images
  - Relative linking for portability
  - No inline CSS or JavaScript

---

## 🚀 Setup & Viewing Instructions

1. **Clone or Download** the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/alpine-bliss-resort.git
````

2. **Open** the project folder in your code editor (e.g., VS Code).
3. **Double-click** `index.html` to open it in your browser.
4. Use the navigation to view both pages.
5. Test the **Contact Form** by filling in the fields and clicking **Submit**.

---

## 👤 Author

**Scott Leishman**
Created for **educational purposes only** — not for commercial use.

---

## 📜 License

This project is intended for learning and demonstration purposes.
All images and text are provided by course materials and should not be used commercially.

```
