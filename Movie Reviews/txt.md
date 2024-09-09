A movie review web application built using HTML, CSS, and JavaScript. The functionality allows users to input a movie title and write a review, which is then displayed on the same page dynamically. The design of the page is styled using Bootstrap for layout and custom CSS for additional styling.

### HTML Structure:
The HTML document is structured into three main sections:
1. **Head**: 
   - External resources such as Bootstrap CSS and JS libraries, jQuery, and Popper.js are included in the head section to style and make the webpage responsive.
   - A link to the custom CSS file (`style.css`) is provided to apply specific styling defined for the project.
   
2. **Body**:
   - The body contains a `container` class to center the content and add padding at the top (`pt-4`).
   - The main heading (`Movies Reviews`) is defined inside a `row` and `col-12` grid system, which Bootstrap uses to organize the layout.
   - An input form is designed with fields for the movie title (input type `text`) and a review (a `textarea`). These fields allow the user to enter data.
   - A button (`Add`) is provided, and when clicked, it triggers the JavaScript function to display the movie review below the input fields.
   - Below the form, the `reviewsContainer` div is used to dynamically display the submitted reviews.
   - The JavaScript (`script.js`) file is loaded at the end of the body for dynamic functionality.

### CSS Styling:
Custom CSS is applied to enhance the appearance and user experience:
- **.reviews-heading**: Styles the main heading with a larger font size (36px), bold weight (700), and a dark color (`#2d3a35`) to make it prominent.
- **.input-label**: This class is applied to the labels (`MOVIE TITLE` and `YOUR REVIEW`). It sets the text color to a grayish hue (`#7b8794`), adjusts font size to 12px, and adds margin for spacing.
- **.title-input**: Styles the input field for the movie title, giving it a border (`1px solid #cbd2d9`), padding for internal spacing (`padding-left: 12px`), and a subtle border radius for rounded corners.
- **.review-textarea**: Similar to the title input field, the textarea is styled with borders, padding, and a rounded design, providing a consistent look and feel.
- **.movie-title**: Applied to the dynamically created movie title headings for each review. The font size is set to 18px, and it is bolded to stand out from the review content.

### JavaScript Functionality:
The core functionality is implemented in the JavaScript file (`script.js`), which handles user input and dynamically updates the DOM to display the review.

1. **Element References**:
   - The `getElementById()` method is used to reference the input elements (`titleInput`, `reviewTextarea`) and the button (`addButton`), as well as the container where the reviews will be displayed (`reviewsContainer`).

2. **Button Click Handler**:
   - An `onclick` event is attached to the "Add" button. When the user clicks the button, the function is triggered to process the input:
     - It retrieves the values from the movie title input (`titleInput.value`) and the review textarea (`reviewTextarea.value`).
     - If the movie title is empty, an alert prompts the user to enter a movie name, preventing an empty submission.
     - If both fields are filled, the function creates new DOM elements to display the review: 
       - A `h1` element for the movie title, styled with the `movie-title` class.
       - A `p` element for the review content.
       - A `hr` element to separate each review visually.
     - These elements are appended to the `reviewsContainer`, and the input fields are cleared after submission for ease of entering new reviews.

### Bootstrap Integration:
Bootstrap’s grid system and layout utilities (such as `container`, `row`, `col-12`, `d-flex`, `justify-content-end`, `btn`, and `btn-primary`) are used to handle responsive design and alignment. This helps avoid custom layout code and ensures that the page adjusts properly on different screen sizes.

### Conclusion:
The project provides a simple yet functional movie review application. It allows users to input movie titles and reviews and dynamically displays them using JavaScript. The combination of Bootstrap for responsive layout, custom CSS for personalized styling, and JavaScript for interactivity makes this project both user-friendly and visually appealing. The logic for handling inputs and dynamically updating the DOM ensures a seamless user experience.
