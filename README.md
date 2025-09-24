README:

Allu Arjun Filmography & Reviews
This project showcases a filmography of Allu Arjun's movies, functioning as a movie review page with details for each film. It features a classy black and yellow theme and an animated intro splash screen. It utilizes HTML, CSS, JavaScript, Bootstrap for responsive design, and jQuery for DOM manipulation and animations.

Features
Responsive Design: Built with Bootstrap to ensure a great viewing experience on various screen sizes.

Classy Black & Yellow Theme: A custom CSS theme provides an elegant and bold aesthetic.

Animated Intro Splash Screen: A captivating intro animation featuring a prominent Allu Arjun image and a loading spinner fades out to reveal the main content.

Dynamic Movie Cards: Each card displays movie details (title, year, rating, genre, summary, and poster), effectively serving as a mini-review or overview for the film.

Hover Effects: Interactive hover animations on movie cards for an enhanced user experience.

Technologies Used
HTML5: For the basic structure of the webpage.

CSS3: For styling, including the custom black & yellow theme and splash screen animations.

JavaScript (ES6+): For dynamic content rendering and interactive elements.

Bootstrap 5.3.3: A popular CSS framework for responsive and mobile-first frontend development.

jQuery 3.7.1: A fast, small, and feature-rich JavaScript library used for DOM traversal and manipulation, event handling, and animation.

Project Structure
The project is organized into three main files:

allu_arjun_movies/
├── index.html
├── style.css
└── script.js
index.html: Contains the main HTML structure, including links to Bootstrap and custom CSS, jQuery and Bootstrap JS CDN links, the intro splash screen, and the main content area.

style.css: Defines the visual styles for the entire application, including the black & yellow theme, responsive adjustments, and intro splash screen animations.

script.js: Holds the movie data, handles the dynamic generation of movie cards using jQuery, and manages the intro splash screen animation logic.

Setup and Usage
To run this project locally, follow these simple steps:

Clone the repository (if applicable) or download the files into a folder named allu_arjun_movies.

Ensure you have the three files: index.html, style.css, and script.js in the allu_arjun_movies directory.

Open the index.html file in your preferred web browser.

The page will first display the animated intro splash screen for a few seconds, then fade out to reveal the full filmography and movie reviews.

Customization
Movie Data: Modify the movies array in script.js to add, remove, or update movie entries. Remember to update the image property with valid URLs for movie posters.

Theme: Adjust the color variables and styles in style.css to change the black and yellow theme to your preferred color scheme.

Intro Animation:

Change the src attribute of the img tag in index.html within the intro-splash div to use a different intro image.

Adjust the setTimeout duration in script.js to change how long the splash screen is displayed.

Modify the fadeOut() and fadeIn() durations in script.js for different animation speeds.

Bootstrap Components: Feel free to integrate more Bootstrap components (e.g., carousels, modals) to further enhance the user interface.
