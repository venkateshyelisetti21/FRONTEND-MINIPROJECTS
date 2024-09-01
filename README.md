# FRONTEND MINIPROJECTS
"Explore a curated collection of front-end mini projects showcasing HTML, CSS, and JavaScript skills. This repository features practical, hands-on examples ranging from interactive web elements to responsive designs, designed to enhance and demonstrate key front-end development techniques."

# 1.  RESTUARANT WEBSITE
This HTML document uses Bootstrap 4.5.2 for styling and layout, creating a responsive webpage for a food-related business. The page is divided into several sections:

Navigation Bar: Includes links to different sections of the page like "Why you choose us?", "Explore menu", "Delivery & payment", and "Follow us". It also features a brand logo on the left side.

Banner Section: Contains a full-screen background image with a headline ("Get Delicious food anytime") and a sub-caption ("it's finger lickin' good."). There are also two buttons: "View button" and "Order now".

Why Choose Us? Section: This section presents reasons to choose the service with three cards highlighting "Food Service," "Fresh Food," and "Best Offers". Each card includes an image, a title, and a description.

Explore Menu Section: Displays different food categories like Non-Veg Starters, Veg Starters, Soups, Fish & Seafood, and Hyderabadi Biryani. Each category is represented by a card with an image, title, and a link to explore more options.

The style is primarily controlled through custom CSS classes defined in the <style> block. The page is designed to be visually appealing with a modern layout and a focus on responsive design, ensuring it looks good on various devices.


# 2.  ECOMMERCE WEBSITE
Building an E-Commerce Static Front-End Website Using HTML and CSS
In today's digital age, creating a compelling and user-friendly e-commerce website is essential for any business looking to thrive online. For this project, I developed a static front-end e-commerce website using HTML and CSS. This approach allowed me to focus on the core aspects of web design and user interface without the complexities of server-side programming or dynamic content generation. Below, I’ll walk you through the key elements of the project, including the design process, features, and technologies used.

### Project Overview
The objective of this project was to design a visually appealing and functional static e-commerce website that showcases products, facilitates user navigation, and enhances the overall shopping experience. While the website is static, it simulates the essential features of a full-fledged e-commerce site, including product listings, a shopping cart, and a checkout process.

### Design and Development Process
Planning and Wireframing

The initial phase involved planning the website’s structure and layout. I created wireframes to outline the essential components of the site, including the homepage, product pages, and shopping cart. These wireframes served as a blueprint for the design and ensured that all key elements were included in the final design.

### HTML Structure

Using HTML, I built the foundational structure of the website. The HTML code defines the layout and content of the site, including headings, paragraphs, images, and links. I organized the content into semantic sections to enhance readability and maintainability. Key HTML elements included:

Header: Contains the site logo, navigation menu, and search bar.
Homepage: Features a hero section with promotional banners, product categories, and featured products.
Product Pages: Display individual product details, including images, descriptions, prices, and “Add to Cart” buttons.
Shopping Cart: Shows a summary of selected items, their quantities, and total price.
Footer: Includes additional navigation links, contact information, and social media icons.
CSS Styling

CSS was used to style the HTML elements and create a visually appealing design. I focused on achieving a clean and modern look that aligns with contemporary e-commerce trends. The key CSS aspects included:

Layout and Positioning: Utilized CSS Flexbox and Grid to create responsive and adaptive layouts. This ensures that the website looks great on all devices, from desktops to mobile phones.
Typography: Chose modern and legible fonts to enhance readability and create a professional appearance.
Color Scheme: Selected a cohesive color palette that reflects the brand’s identity and creates a pleasant visual experience.
Buttons and Links: Styled interactive elements such as buttons and links to be visually distinct and user-friendly. Hover effects were added to improve interactivity.
Product Images: Ensured that product images are responsive and properly aligned to maintain consistency across different screen sizes.
Responsive Design

To ensure that the website is accessible and functional on various devices, I implemented responsive design principles using CSS media queries. This approach allows the site to adapt to different screen sizes and orientations, providing an optimal viewing experience for users.

### Testing and Optimization

Thorough testing was conducted to identify and resolve any issues related to layout, functionality, or performance. I tested the website on multiple devices and browsers to ensure compatibility and responsiveness. Additionally, I optimized the site’s performance by minimizing CSS file sizes and optimizing images to reduce load times.

### Key Features
Homepage Design

The homepage serves as the entry point to the site and is designed to capture users’ attention with visually appealing elements. It includes a hero section with high-quality images and promotional banners that highlight current sales or new arrivals. Below the hero section, users can browse product categories and view featured products.

### Product Listings

Each product page displays detailed information about individual products, including high-resolution images, descriptions, prices, and customer reviews. The “Add to Cart” button allows users to easily add items to their shopping cart.

### Shopping Cart

The shopping cart provides users with an overview of their selected items, including product names, quantities, prices, and the total amount. Users can modify quantities or remove items from the cart before proceeding to the checkout process.

### Navigation and Usability

The navigation menu is designed to be intuitive and user-friendly, providing easy access to key sections of the site, such as product categories, the shopping cart, and user account settings. The search bar allows users to quickly find specific products.

### Footer Information

The footer includes essential information such as contact details, additional navigation links, and social media icons. This ensures that users have access to important information and can connect with the brand through various channels.

### Conclusion
Developing this static e-commerce website using HTML and CSS has been an enriching experience, allowing me to apply my front-end development skills in a practical context. The project highlights the importance of a well-structured layout, responsive design, and user-friendly interface in creating an effective online shopping experience.

While this website is static, the principles and techniques applied can be extended to dynamic e-commerce sites with additional functionality and back-end integration. The skills acquired through this project will serve as a foundation for future development endeavors and contribute to my growth as a front-end developer.

# 3.  LIGHT SWITCH ON-OFF WEBSITE
The core functionality of this web page is to simulate a light switch that toggles a light bulb on and off, along with a corresponding visual change to a cat image. Below is a detailed description of the key components and functionality:

### HTML Structure
The HTML structure begins with the necessary <head> tags, where external stylesheets and scripts are linked. These include Bootstrap’s CSS and JavaScript, jQuery, and Popper.js, which are essential for responsive design and user interaction.

The <body> of the document contains the primary content and styling information. A <style> tag within the body defines custom CSS for the webpage, setting the tone for the dark background (dark-bg class) and designing elements like buttons and images.

### CSS Styling
Custom CSS is employed to style various elements such as:

Background and Layout: The .dark-bg class provides a dark background color for the page, enhancing the visual contrast with the bright bulb and cat images.
Images: The .bulb-image and .cat-image classes define specific widths for the images displayed on the page, ensuring they are consistently sized.
Switch Board: The .switch-board class defines the background color, size, and padding for the switch panel, which houses the buttons and status message. This panel has rounded corners for a modern look.
Buttons: The buttons are styled with specific dimensions, colors, and fonts. The on-switch and off-switch classes ensure that the buttons are easily distinguishable, with color changes that signify their active status.
JavaScript Functionality
The interactivity of the webpage is managed through JavaScript functions that respond to user actions:

### Switch Off (switchOff function):

Changes the bulb image to depict a bulb that is turned off.
Updates the cat image to show the cat with closed eyes, indicating a response to the light being turned off.
Changes the text of the switch status to "Switched Off."
Modifies the background color of the buttons, making the "OFF" button appear active (light grey) and the "ON" button appear ready to be clicked (green).
Switch On (switchOn function):

Changes the bulb image back to one that shows the bulb turned on.
Restores the original cat image with open eyes, indicating that the light is on.
Updates the switch status text to "Switched On."
Alters the button colors, making the "ON" button appear active (light grey) and the "OFF" button appear inactive (red).
Interaction and User Experience
When the user clicks the "ON" or "OFF" buttons, the JavaScript functions execute and update the content dynamically, providing immediate visual feedback. The button colors and images change, giving a sense of control over the simulated light bulb, and the text content updates to reflect the current state of the bulb.

### External Resources
The code references images hosted on a cloud platform for the bulb and cat visuals. These images change based on the user's interactions with the switches.

### Conclusion
Overall, the code demonstrates an effective use of HTML, CSS, and JavaScript to create an interactive web page that responds to user input. Bootstrap enhances the visual appeal and responsiveness of the design, while the custom JavaScript ensures the webpage is engaging and dynamic. This code could serve as a learning example for beginners or as a basis for more complex interactive web applications.

# 4. COLOR PICKER

### HTML Structure
The HTML document begins with the <!DOCTYPE html> declaration, which defines the document type and version. The html tag encapsulates the entire document, which includes two main sections: the head and the body.

### Head Section
The head section contains links to external resources:

Bootstrap CSS: A link to the Bootstrap framework’s CSS file is provided via a CDN (Content Delivery Network). Bootstrap is a popular CSS framework that offers pre-designed components and styles to ensure a responsive and consistent design across devices.

jQuery and Bootstrap JS: The section includes jQuery and Bootstrap's JavaScript files, which are also loaded via CDN. These scripts provide functionality for dynamic behavior and interactivity. jQuery is a widely used JavaScript library that simplifies DOM manipulation, event handling, and AJAX interactions. Bootstrap’s JavaScript components require jQuery to function.

### Body Section
The body of the document contains a style block with custom CSS and the main content wrapped within the container div.

### Custom CSS
.bg: A class defining a white background and full viewport height (100vh) for the main content section.
.heading: Sets the font family to "Roboto" for the heading element.
.button1, .button2, .button3, .button4: These classes define the style for the four buttons, including padding, border-radius, background colors, and text colors. Each button has a different background color corresponding to the color it will apply when clicked.
.color-para-bg: Defines the background color as black with white text, rounded corners, and bold, medium-sized text for the paragraph that displays the selected background color.
.span-color: A class that sets the text color to a light blue shade.
Main Content
The content is wrapped inside a container div that uses Bootstrap's grid system. The layout centers the main content horizontally on the page using two col classes, with the central column occupying six out of twelve grid spaces (col-lg-6).

Heading: A centered heading with the text "Color Picker" styled by the .heading class.
Buttons: Four buttons are displayed below the heading. Each button has an onclick event that triggers a corresponding JavaScript function to change the background color.
Paragraph: Below the buttons, a paragraph displays the current background color. The paragraph uses the .color-para-bg class for styling, and the color code is displayed inside a span element with the id of "spanName".
JavaScript
The script is linked externally and contains four functions—buttn1(), buttn2(), buttn3(), and buttn4()—each corresponding to a button.

Event Handling: When a button is clicked, its respective function is triggered.
DOM Manipulation: The background color of the div with the id "background" is changed, and the color code is updated in the span element with the id "spanName".
Each function updates the backgroundColor of the bg element and the textContent of the spanName element to match the selected color.

### Conclusion
This code provides a clean and straightforward user interface where users can interactively change the background color of a webpage section by clicking on buttons. The use of Bootstrap ensures that the design is responsive, while custom CSS and JavaScript enable the interactive functionality.


# 5. COUNTER APPLICATION

The application utilizes HTML for the structure, CSS for styling, and JavaScript for the interactivity. Additionally, the Bootstrap framework is integrated for basic layout and responsiveness.

### HTML Structure
The HTML file begins with the <!DOCTYPE html> declaration, ensuring that the document is recognized as HTML5. The <head> section includes links to external resources, specifically Bootstrap and jQuery libraries. Bootstrap is used for styling and layout management, while jQuery facilitates easy DOM manipulation and event handling.

Inside the <body> tag, custom CSS is defined to style specific elements of the application. The CSS styles define the background color, text alignment, font properties, and button styles. The primary container of the application, represented by the div element with the class bg-container, is centrally aligned using Bootstrap's flexbox utilities (d-flex, flex-column, justify-content-center, text-center), ensuring that the content is vertically and horizontally centered within the viewport.

The application features a heading (Counter), a paragraph element (<p>) to display the counter value, and three buttons (DECREASE, RESET, INCREASE). These buttons trigger the corresponding JavaScript functions (onDecrement, onReset, onIncrement) when clicked.

### JavaScript Interactivity
The interactivity of the counter application is handled through JavaScript, which is linked in the HTML via an external script file, Counter-application.js. This script contains three primary functions that control the behavior of the counter:

onIncrement(): This function is executed when the "INCREASE" button is clicked. It retrieves the current counter value from the counterValue element, converts it to an integer, increments it by one, and updates the displayed value. Additionally, the text color of the counter changes based on the value: green for positive numbers, red for negative, and black for zero. This visual feedback enhances user experience by immediately conveying whether the counter is positive, negative, or neutral.

onDecrement(): Triggered by the "DECREASE" button, this function behaves similarly to onIncrement(), but it decreases the counter value by one. The color of the counter is also updated according to the value.

onReset(): When the "RESET" button is clicked, this function resets the counter value to zero and changes the text color back to black, indicating a neutral state.

User Experience and Functionality
This counter application is designed to be intuitive and user-friendly. The minimalist design, coupled with color-coded feedback, makes it easy for users to understand the current state of the counter. The buttons are clearly labeled, and their functionality is straightforward, ensuring that users can interact with the counter without any confusion.

The use of Bootstrap ensures that the application is responsive, meaning it will display correctly on various devices and screen sizes. The CSS customizations align with the overall design, providing a consistent look and feel.

In conclusion, this counter application serves as a fundamental example of how HTML, CSS, and JavaScript can be combined to create interactive web applications. It effectively demonstrates the power of JavaScript in manipulating the DOM and providing real-time feedback to users, all within a clean and responsive interface facilitated by Bootstrap.


# 6.   GUESSING NUMBER GAME

### Number Guessing Game: An Overview

This project is a simple yet engaging number-guessing game built with HTML, CSS, and JavaScript. The objective of the game is to guess a randomly generated number between 1 and 100. This game offers an interactive way for users to test their guessing skills, with immediate feedback provided for each guess. The project also leverages Bootstrap for responsive design, ensuring a user-friendly experience across different devices.

### HTML Structure

The HTML file is the foundation of the game’s structure. It includes references to Bootstrap's CSS and JS libraries for styling and interactivity. The document is organized into two main sections:

1. **Header Section**:
   - The `head` tag includes links to Bootstrap's CSS, jQuery, Popper.js, and Bootstrap's JavaScript. These libraries are crucial for ensuring that the game is responsive and interactive.

2. **Body Section**:
   - The `body` tag contains the game's user interface elements. The layout is structured using Bootstrap's grid system, ensuring that the game is displayed properly on all screen sizes.
   - The game is wrapped inside a `container-fluid` div with a `bg-container` class, setting the background color to blue and occupying the entire viewport height.
   - Inside this container, the first row presents an image related to the game, accompanied by a brief description encouraging the user to find the right number between 1 and 100.
   - The second row contains the main game interface, where the user interacts with the game. This includes a heading, an input field for the user's guess, a button to submit the guess, and a paragraph element to display the result.

### CSS Styling

The styling is handled within a `<style>` block in the `body` section, with custom classes used to enhance the game's visual appeal:

- **bg-container**: Sets the overall background color of the game to a light blue shade.
- **guess-game-img**: Ensures that the game-related image is responsive, filling the width of its container.
- **game-description**: Styles the game description with the Roboto font, setting the size, weight, and color to match the overall design theme.
- **guess-heading**: Defines the appearance of the game's main heading, including a bold font style and white color for better visibility against the blue background.
- **user-input**: Styles the input field where the user enters their guess, making it larger and more readable.
- **game-result**: Styles the result message that displays after each guess, ensuring it is clearly visible to the user.
- **check-guess**: Customizes the appearance of the button used to submit the user's guess, with rounded corners and padding for a modern look.

### JavaScript Logic

The core functionality of the game is implemented in the `guessing-game.js` script, which is referenced at the bottom of the HTML file. This script is responsible for generating the random number and evaluating the user's guesses.

1. **Variable Declarations**:
   - `gameResult`: Links to the DOM element where the result of the user's guess is displayed.
   - `userInput`: References the input field where the user enters their guess.
   - `randomNum`: Generates a random number between 1 and 100, which the user must guess.

2. **checkGuess() Function**:
   - This function is triggered when the user clicks the "Check" button. It reads the user's input, converts it to an integer, and compares it to the randomly generated number.
   - Based on the comparison, the function provides feedback:
     - If the guess is too high, the message "It's too High, Try again..." is displayed with a blue background.
     - If the guess is too low, the message "It's too Low, Try again..." is displayed with the same blue background.
     - If the guess is correct, a congratulatory message "Congrats! You got it..." is shown, with the background turning green.
     - If the input is invalid (e.g., non-numeric), an error message "Please provide valid Input" appears with a red background.

### Conclusion

This project serves as a practical example of how to combine HTML, CSS, and JavaScript to create an interactive web-based game. By leveraging Bootstrap for styling and responsiveness, it ensures a smooth user experience. The straightforward logic implemented in JavaScript makes it an excellent starting point for beginners looking to understand DOM manipulation and conditional statements in a fun and engaging way. This code can be further enhanced with additional features, such as keeping score or adding difficulty levels, making it a versatile template for more advanced projects.

