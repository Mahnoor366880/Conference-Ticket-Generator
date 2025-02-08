# Conference Ticket Generator

## Overview
The **Conference Ticket Generator** allows users to fill out a form to generate their personalized conference tickets. This project emphasizes form validation, responsive design, and accessibility. 

### Users should be able to:
- Complete the form with their details.
- Receive form validation messages if:
  - Any field is missed.
  - The email address is not formatted correctly.
  - The avatar upload is too big or the wrong image format.
- Complete the form using only their keyboard.
- Have inputs, form field hints, and error messages announced on their screen reader.
- See the generated conference ticket when they successfully submit the form.
- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

## The Challenge
### Users should be able to:
- Fill out a form with their details.
- Receive real-time validation messages.
- Generate a visual conference ticket upon form submission.
- The site should work on both desktop and mobile devices.

## Screenshots
- **Desktop View:** ![Desktop View](./images/Desktop%20Ticket.png)
- **Mobile View:** ![Mobile View](./images/mobile.png)
- **Mobile View:** ![Mobile View](./images/mobile2.png)

## Links
- [Solution URL](https://github.com/Mahnoor366880/Conference-Ticket-Generator.git)
- [Live Site URL](https://mahnoor366880.github.io/Conference-Ticket-Generator/)

## My Process

### Built With
- **Semantic HTML5** markup
- **Tailwind CSS** for responsive design
- **JavaScript** for form validation and event handling
- Mobile-first workflow

### Key Code Snippets

#### Form Validation:
```js
form.addEventListener('submit', (e) => {
  if (!email.value.includes('@')) {
    alert('Please enter a valid email address.');
    e.preventDefault();
  }
});
const maxFileSize = 500 * 1024; // 500KB
if (file.size > maxFileSize) {
  alert('File size should not exceed 500KB.');
  return;
}
const maxFileSize = 500 * 1024; // 500KB
if (file.size > maxFileSize) {
  alert('File size should not exceed 500KB.');
  return;
}


###What I Learned

This project was an excellent opportunity to practice:

Form validation
File handling
Responsive design
Accessibility
###Continued Development

##Future improvements:

Enhancing the file upload UI with better drag-and-drop animations.
Adding server-side validation for better security.
Implementing ticket customization options for users.
###Useful Resources

MDN Web Docs - Comprehensive resource for web development.

###Author

GitHub: @Mahnoor366880
LinkedIn: Mahnoor Shahbaz
###Acknowledgments

A big thanks to Frontend Mentor for their practice challenges and insightful community feedback

