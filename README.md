# Personal-Portfolio-Website

This project is a personal portfolio website designed to showcase various web development projects and skills. The website includes sections for an introduction, skills, projects, and contact form. It is built with a focus on providing a professional presentation of the developer's capabilities, complete with interactive elements and modern web design techniques.

Features
Responsive Design: Fully responsive layout that adapts to different screen sizes (desktop, tablet, mobile).
Navigation: Clear and easy-to-use navigation with links to sections like Home, About, Projects, and Contact.
Typewriter Animation: Interactive typewriter effect on the homepage that cycles through different roles (Developer, Designer, Freelancer) dynamically.
Project Gallery: A section showcasing various web development projects with image lightbox support for detailed viewing.
Skills Section: Visual representation of key skills using progress bars and icons.
Contact Form: Integrated contact form with Formspree form submission support and Google reCAPTCHA for spam prevention. Additionally, Netlify form submission is used for handling the form data seamlessly.
Animations: Includes CSS animations (via Animate.css) for enhanced interactivity and smooth transitions.
Carousel: Owl Carousel is used for displaying multiple project images or testimonials in an attractive, sliding gallery.
Technologies Used
Frontend Technologies:
HTML5: Markup language for structuring the website's content.
CSS3: Used for layout and styling. Includes media queries for responsiveness and advanced CSS animations for smooth transitions.
Owl Carousel: A powerful jQuery plugin used to create responsive, touch-enabled carousels for displaying images or project descriptions.
Animate.css: A library that provides cross-browser CSS animations for a dynamic, engaging user experience
Font Awesome: For adding vector icons to the webpage, such as social media links and contact icons.
Lightbox2: For displaying images in a modal view with the ability to scroll through them, enhancing project image previews.
JavaScript:
jQuery: Used for DOM manipulation and managing interactive elements.
Typewriter.js: A custom JavaScript library to create the typing effect for the roles displayed on the homepage
Additional Technologies Used
SASS: This project uses SASS for efficient styling and easier management of CSS. The project structure includes multiple partials for different components (e.g., _header.scss, _footer.scss, _home.scss, etc.) to keep the styles modular and organized. The SASS files are compiled into minified CSS using the sass command in the package.json file:
scss folder for source SASS files.
public/css folder for compiled CSS.
Command to run SASS in watch mode: npm run scss
JSON:
package.json: This file is used to manage project dependencies such as Lightbox2 for image galleries and Owl Carousel for responsive carousels. It also contains the necessary script to compile SASS files.
package-lock.json: Ensures that the dependencies and versions used in the project are consistent across environments
Backend (Optional for Form Handling):
Netlify: Used for form handling with automatic submission via Netlify forms. This helps in managing user contact submissions directly from the website without needing a traditional backend.
Formspree: Integrated into the contact form for easy submission handling. When a user fills out the contact form, it automatically sends the data to your email, offering a simple and efficient solution for contact form management
Design:
Google Fonts: The 'Prompt' font is used for a clean, modern look that is easy to read across devices
Custom CSS: Styled for a minimalist, modern design with a focus on clarity and user engagement. The layout uses Flexbox and CSS Grid to create responsive and well-aligned content
