
# Natours Landing Page

**Natours** is a visually appealing and responsive landing page designed for a fictional travel company that offers exciting tours for adventurous people. This project demonstrates advanced CSS and SASS techniques, including animations, responsive design, and modular styling.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [File Structure](#file-structure)
5. [How to Use](#how-to-use)
6. [Available Scripts](#available-scripts)
7. [Future Enhancements](#future-enhancements)
8. [Credits](#credits)

---

## **Project Overview**

The project focuses on building a modern and interactive landing page with the following sections:
- A **navigation bar** with a hamburger menu for mobile devices.
- A **hero section** with an eye-catching background image and a call-to-action button.
- **About, Features, Tours, and Stories sections** to showcase the company's offerings and testimonials.
- A **booking form** for users to reserve tours.
- A **footer** with links to the company’s information.

The layout and components are fully responsive, ensuring a seamless experience across all devices.

---

## **Features**

### **Navigation**
- Mobile-friendly hamburger menu with a background overlay animation.
- Smooth transitions for opening and closing the menu.

### **Hero Section**
- A large background image with a gradient overlay.
- Animated text with a call-to-action button.

### **About Section**
- Two-column layout with descriptive text on the left and responsive images on the right.

### **Features Section**
- Highlights four key features using icons, animations, and concise text.

### **Tours Section**
- Interactive cards that showcase popular tours with hover flip animations.
- Detailed pricing and call-to-action buttons.

### **Stories Section**
- Features customer testimonials with images, blur effects, and captions.
- Background video adds a dynamic and immersive touch.

### **Booking Section**
- Responsive form for users to book tours.
- Includes form validation for inputs and styled radio buttons.

### **Footer**
- Contains navigational links and company information.

---

## **Technologies Used**

### **Frontend**
- **HTML5:** Semantic structure and accessibility.
- **SASS (SCSS):** Modular, maintainable styles with variables, mixins, and nested rules.
- **CSS3:** Animations, transitions, and advanced layouts.
- **JavaScript (optional):** Enhances functionality where needed.

### **Tooling**
- **Sass:** Compiles SCSS to CSS.
- **PostCSS (with Autoprefixer):** Adds vendor prefixes for cross-browser compatibility.
- **Live Server:** Provides a development server with hot reloading.
- **npm-run-all:** Orchestrates multiple scripts.

---

## **File Structure**

```
project-folder/
│
├── css/                 # Compiled and processed CSS files
│   ├── style.css        # Final production CSS
│   ├── icon-font.css    # Icon fonts
│   └── style.prefix.css # Prefixed CSS
│
├── img/                 # Images used in the project
│   ├── logo-green.png   # Logo images
│   ├── nat-*.jpg        # Tour images
│   └── video.mp4        # Background video
│
├── sass/                # Source SCSS files
│   ├── abstracts/       # Mixins, variables, functions
│   ├── base/            # Resets, typography, utilities
│   ├── components/      # Components like buttons, forms
│   ├── layout/          # Structural styles (header, footer)
│   ├── pages/           # Page-specific styles
│   └── main.scss        # Main entry point for Sass
│
├── index.html           # Main HTML file
├── package.json         # Node.js package configuration
└── README.md            # Documentation file
```

---

## **How to Use**

### **Setup**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/natours.git
   cd natours
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

   This will:
   - Launch the project in a browser using **Live Server**.
   - Watch for changes in `.scss` files and compile them into CSS.

4. **Build the production-ready CSS:**
   ```bash
   npm run build:css
   ```

---

## **Available Scripts**

The following scripts are available in the `package.json`:

- **`npm start`**: Starts the development environment with live server and Sass watch.
- **`npm run watch:sass`**: Watches for changes in `.scss` files and compiles them to CSS.
- **`npm run devserver`**: Starts the live server.
- **`npm run build:css`**: Full production build pipeline:
  1. Compiles Sass to CSS.
  2. Concatenates files.
  3. Adds vendor prefixes.
  4. Compresses the final CSS.

---

## **Credits**

- **Oron Schrager** - Developer and creator.
- **Jonas Schmedtmann** - Inspiration from his Advanced CSS and Sass course.
- **Tools and Libraries:**
  - [Sass](https://sass-lang.com/)
  - [PostCSS](https://postcss.org/)
  - [Autoprefixer](https://github.com/postcss/autoprefixer)
  - [Live Server](https://www.npmjs.com/package/live-server)

---

