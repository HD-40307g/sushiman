# Sushiman 
![Sushiman Logo](/public/sushi.png)

A modern, responsive website designed for **Sushiman**, a Japanese cuisine restaurant. The site provides an immersive user experience with animations, a vibrant design, and smooth navigation.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [CSS Modules](#css-modules)
- [JavaScript Modules](#javascript-modules)
- [Accessibility and SEO](#accessibility-and-seo)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Fully Responsive Design**: Optimized for all screen sizes from mobile to desktop.
- **Smooth Animations**: Integrates AOS (Animate on Scroll) for smooth scroll animations.
- **Lazy Loading Images**: Improves performance by only loading images as needed.
- **Accessible Design**: Follows ARIA standards and best practices for navigation and content.
- **SEO-Ready**: Includes metadata and structured content to optimize search engine performance.

---

## Getting Started

### Prerequisites
- Basic knowledge of HTML, CSS, and JavaScript.
- Ensure you have a live server setup (like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code) to view the project locally.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/HD-40307g/sushiman.git
   cd sushiman-website
   ```
2. **Install dependencies** (optional for AOS animations and any additional libraries used):
   ```bash
   npm install
   ```

3. **Run the project**:
   - Open `index.html` in your browser or use a live server for local development.

---

## Project Structure

The project is structured to keep styles, scripts, and assets organized.

```plaintext
sushiman/
├── assets/                      # Contains image and icon files
├── css/                         # Section styles and main style file
│   ├── sections/                # All sections CSS files
│   │    ├── style.css           # Main CSS file importing CSS modules
│   │    ├── header.css          # Header section styling
│   │    ├── hero.css            # Hero section styling
│   │    ├── about-us.css        # About Us section styling
│   │    ├── popular-foods.css   # Popular Foods section styling
│   │    ├── trending.css        # Trending section styling
│   │    ├── subscription.css    # Subscription section styling
│   │    └── footer.css          # Footer section styling
│   └── style.css                # Main CSS file
├── js/                          # Directory with JavaScript files
│   └── script.js                # Main JavaScript file (ES6 module)
├── public                       # Logo and favicon files
├── LICENSE                      # Standard MIT License
├── index.html                   # Main HTML file
├── package-lock.json            # Exact dependency versions for install
├── package.json                 # Project dependencies and scripts
└── README.md                    # Project README file
```

---

## CSS Modules

Each section of the page has its own CSS module. This structure keeps styles modular and manageable.

### Main CSS (`css/style.css`)
- Imports individual CSS modules to combine all styles into a single file.
- Applies base and global styles, including typography, colors, and utility classes.

### Section Modules
- **`header.css`**: Contains styles for the navigation bar and logo.
- **`hero.css`**: Styles for the hero section, including image overlay and introductory text.
- **`about-us.css`**: Manages styles for the About Us section and related imagery.
- **`popular-foods.css`**: Manages styles for the popular foods carousel and filters.
- **`trending.css`**: Includes styling for trending items and icon lists.
- **`subscription.css`**: Styles the subscription form for capturing user email.
- **`footer.css`**: Contains styling for the footer section, including social media links and navigation.

### Animation on Scroll (AOS)
- AOS library is used for scroll animations. All elements with `data-aos` attributes will animate as they enter the viewport.

---

## JavaScript Modules

The JavaScript files use ES6 module syntax for modularity and simplicity.

- **`script.js`**: The main JavaScript file responsible for DOM manipulation and event handling.

### Importing Modules
Ensure `script.js` is imported as a module in the HTML file:
```html
<script src="js/script.js" type="module"></script>
```

---

## Accessibility and SEO

This project is optimized for accessibility and search engine visibility:

- **ARIA roles**: Key roles are applied for screen readers (e.g., `role="navigation"`).
- **Alt Text**: Meaningful `alt` text is provided for images, and decorative images have empty `alt=""` attributes.
- **Meta Tags**: Includes essential meta tags for description, viewport, and social sharing.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
