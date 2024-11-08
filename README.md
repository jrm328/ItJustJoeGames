
# Its Just Joe Games - Website

Welcome to the official website of **Its Just Joe Games**, a media company dedicated to cloud gaming insights, indie game development, and tech innovation. This website provides users with engaging content, including a podcast, game reviews, and upcoming indie game releases.

## Table of Contents

- [About](#about)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Hosting on GitHub Pages](#hosting-on-github-pages)
- [License](#license)

## About

This website serves as the online presence for **Its Just Joe Games**, featuring:
- Engaging **Hero** and **About** sections to introduce the brand.
- Content sections for YouTube videos, podcasts, and game projects.
- Links to social platforms and resources for the gaming community.

It’s built with a minimalistic design and a sleek black-and-yellow color scheme, using HTML, CSS, and JavaScript to provide a smooth user experience.

## Project Structure

```plaintext
.
├── index.html          # Main HTML file
├── style.css           # Main CSS file for styling
├── script.js           # Optional JavaScript file (if needed for further interactivity)
├── assets/             # Directory for images, icons, etc.
├── README.md           # Project documentation
└── pattern.png         # Background pattern for the hero section
```

## Technologies Used

- **HTML5** for structure and semantic content.
- **CSS3** with Tailwind CSS for utility styling, including custom styles for animations and effects.
- **Font Awesome** for social media icons.
- **AOS (Animate on Scroll)** for scroll animations.
- **Google Fonts** for typography (Montserrat and Roboto).

## Getting Started

To view and edit the project locally, follow these steps:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/itsjustjoegames.git
   ```
   
2. **Navigate to Project Directory**  
   ```bash
   cd itsjustjoegames
   ```
   
3. **Open index.html in your Browser**  
   Open `index.html` in your preferred web browser to view the site locally.

## Customization

### Changing Colors
To customize the black-and-yellow color scheme, edit the color values in `style.css`.

### Adding New Sections
To add more content sections:
1. Create a new `<section>` element in `index.html`.
2. Style the section as desired in `style.css`.
3. Optionally, use AOS attributes for scroll animations (e.g., `data-aos="fade-up"`).

### Updating Social Links
Social links can be updated directly in the `<header>` and `<footer>` sections of `index.html` by modifying the href values for each social icon.

## Hosting on GitHub Pages

To host this project on GitHub Pages:

1. Go to your repository's **Settings** > **Pages**.
2. Under "Source," select the `main` branch and the root directory (or `/docs` if you use a `/docs` folder).
3. Save the changes, and GitHub will provide a URL where your site is accessible.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

**Its Just Joe Games** - Bringing you the future of cloud gaming and indie development.
