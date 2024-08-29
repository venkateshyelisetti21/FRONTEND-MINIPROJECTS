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

Project Overview
The objective of this project was to design a visually appealing and functional static e-commerce website that showcases products, facilitates user navigation, and enhances the overall shopping experience. While the website is static, it simulates the essential features of a full-fledged e-commerce site, including product listings, a shopping cart, and a checkout process.

Design and Development Process
Planning and Wireframing

The initial phase involved planning the website’s structure and layout. I created wireframes to outline the essential components of the site, including the homepage, product pages, and shopping cart. These wireframes served as a blueprint for the design and ensured that all key elements were included in the final design.

HTML Structure

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

Testing and Optimization

Thorough testing was conducted to identify and resolve any issues related to layout, functionality, or performance. I tested the website on multiple devices and browsers to ensure compatibility and responsiveness. Additionally, I optimized the site’s performance by minimizing CSS file sizes and optimizing images to reduce load times.

Key Features
Homepage Design

The homepage serves as the entry point to the site and is designed to capture users’ attention with visually appealing elements. It includes a hero section with high-quality images and promotional banners that highlight current sales or new arrivals. Below the hero section, users can browse product categories and view featured products.

Product Listings

Each product page displays detailed information about individual products, including high-resolution images, descriptions, prices, and customer reviews. The “Add to Cart” button allows users to easily add items to their shopping cart.

Shopping Cart

The shopping cart provides users with an overview of their selected items, including product names, quantities, prices, and the total amount. Users can modify quantities or remove items from the cart before proceeding to the checkout process.

Navigation and Usability

The navigation menu is designed to be intuitive and user-friendly, providing easy access to key sections of the site, such as product categories, the shopping cart, and user account settings. The search bar allows users to quickly find specific products.

Footer Information

The footer includes essential information such as contact details, additional navigation links, and social media icons. This ensures that users have access to important information and can connect with the brand through various channels.

Conclusion
Developing this static e-commerce website using HTML and CSS has been an enriching experience, allowing me to apply my front-end development skills in a practical context. The project highlights the importance of a well-structured layout, responsive design, and user-friendly interface in creating an effective online shopping experience.

While this website is static, the principles and techniques applied can be extended to dynamic e-commerce sites with additional functionality and back-end integration. The skills acquired through this project will serve as a foundation for future development endeavors and contribute to my growth as a front-end developer.

# 3.  LIGHT SWITCH ON-OFF WEBSITE
The core functionality of this web page is to simulate a light switch that toggles a light bulb on and off, along with a corresponding visual change to a cat image. Below is a detailed description of the key components and functionality:

HTML Structure
The HTML structure begins with the necessary <head> tags, where external stylesheets and scripts are linked. These include Bootstrap’s CSS and JavaScript, jQuery, and Popper.js, which are essential for responsive design and user interaction.

The <body> of the document contains the primary content and styling information. A <style> tag within the body defines custom CSS for the webpage, setting the tone for the dark background (dark-bg class) and designing elements like buttons and images.

CSS Styling
Custom CSS is employed to style various elements such as:

Background and Layout: The .dark-bg class provides a dark background color for the page, enhancing the visual contrast with the bright bulb and cat images.
Images: The .bulb-image and .cat-image classes define specific widths for the images displayed on the page, ensuring they are consistently sized.
Switch Board: The .switch-board class defines the background color, size, and padding for the switch panel, which houses the buttons and status message. This panel has rounded corners for a modern look.
Buttons: The buttons are styled with specific dimensions, colors, and fonts. The on-switch and off-switch classes ensure that the buttons are easily distinguishable, with color changes that signify their active status.
JavaScript Functionality
The interactivity of the webpage is managed through JavaScript functions that respond to user actions:

Switch Off (switchOff function):

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

External Resources
The code references images hosted on a cloud platform for the bulb and cat visuals. These images change based on the user's interactions with the switches.

Conclusion
Overall, the code demonstrates an effective use of HTML, CSS, and JavaScript to create an interactive web page that responds to user input. Bootstrap enhances the visual appeal and responsiveness of the design, while the custom JavaScript ensures the webpage is engaging and dynamic. This code could serve as a learning example for beginners or as a basis for more complex interactive web applications.
