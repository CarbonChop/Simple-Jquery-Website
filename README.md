# Simple-Jquery-Website
Create a single HTML page that includes the following features, utilizing jQuery to handle interactions and animations.

1. Structure of the Page:
Your HTML page should include the following sections:

A Navigation Bar with 3 items (e.g., "Home", "About", "Contact") that will toggle visibility of corresponding content sections when clicked.
- An Image Gallery with 6 images. When an image is clicked, it should expand to a larger size.
- A Form with at least 3 fields (e.g., Name, Email, and Message) that validates inputs on submit. If the form is valid, it should display a success message; if not, show an error message for each invalid field.
- A To-Do List with a button that allows users to add new tasks. Each task should be removable with a delete button next to it.
- An Interactive Button that changes color when hovered over and changes back when the mouse leaves.

2. Requirements:

a. Navigation Bar:
- Use jQuery to toggle between "Home", "About", and "Contact" sections when the corresponding nav item is clicked. Ensure only one section is visible at a time.
  - Hint: Use `.click()`, `.hide()`, `.show()`, and `.fadeIn()`/`.fadeOut()` methods.

b. Image Gallery:
- Display six images in a grid layout.
- When an image is clicked, it should expand to a larger size in the center of the screen.
  - Hint: You may need to use `.click()` for interaction and `.animate()` or `.fadeIn()` for the expanding effect.

c. Form Validation:
- Create a simple form with:
  - A Name field (required).
  - An Email field (must be a valid email).
  - A Message field (required, min 10 characters).
- Upon clicking the submit button, if any of the fields are invalid:
  - Highlight the field with a red border.
  - Show an error message next to the invalid field.
- If all fields are valid, display a success message below the form.
  - Hint: Use `.val()`, `.css()`, and `.text()` methods to access and modify form elements.

d. To-Do List:
- Provide an input field and a button labeled "Add Task".
- When the "Add Task" button is clicked, add a new task to the list with the text from the input field.
- Each task should have a "Delete" button next to it. When clicked, the task should be removed from the list.
  - Hint: Use `.append()`, `.on()`, and `.remove()` methods.

e. Interactive Button:
- Create a button with the text "Hover me!".
- When the user hovers over the button, it should change color (e.g., from blue to green).
- When the mouse leaves, it should change back to its original color.
  - Hint: Use `.hover()` for mouseenter and mouseleave events, and `.css()` for changing styles.

3. Additional Features (Optional for Extra Credit):
- Smooth Scroll: Add smooth scrolling to the page when navigation links are clicked.
  - Hint: Use the `.animate()` method to scroll smoothly to each section.
  
- Dynamic Date and Time: Display the current date and time in the footer, and update it every second using jQuery.
  - Hint: Use `setInterval()` with `.text()` to update the time.

4. Deliverables:
- Submit a single `.html` file containing all your code (including jQuery links).
- The page should be responsive and functional across different browsers.
- Ensure that your code is well-commented and follows best practices for clean, readable code.