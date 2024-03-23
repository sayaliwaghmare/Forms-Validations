# Forms-Validations
Below is a step-by-step explanation, documentation, and the challenges faced during the process of both the Forms:

Documentation and Explanation

HTML Structure

Contact Form:
 Consists of two input fields (Name and Email) and a submit button.
 Each input field has a corresponding error message placeholder.
Login Form:
 Consists of two input fields (Email and Password) and a submit button.
 Each input field has a corresponding error message placeholder.

CSS Styling

 Styles the forms to be centered on the page.
 Provides styling for input fields, buttons, and error messages for a clean and user-friendly interface.

JavaScript Validation

Contact Form Validation

1.Event Listener:
  Listens for the form submission event.
2.Prevent Default:
  Prevents the default form submission behavior.
3.Input Retrieval:
  Retrieves the values of the Name and Email input fields.
4.Validation:
  Checks if the Name field is empty.
  Checks if the Email field is empty and validates its format using a regular expression.
5.Error Handling:
  Displays appropriate error messages below the input fields if validation fails.
6.Form Submission:
  If validation passes, an alert is shown, and the form is reset.
  
Login Form Validation
1.Event Listener:
  Listens for the form submission event.
2.Prevent Default:
  Prevents the default form submission behavior.
3.Input Retrieval:
  Retrieves the values of the Email and Password input fields.
4.Validation:
  Checks if the Email field is empty.
  Checks if the Email field is empty and validates its format using a regular expression.
  Checks if the Password field is empty.
5.Error Handling:
  Displays appropriate error messages below the input fields if validation fails.
6.Form Submission:
  If validation passes, an alert is shown, and the form is reset.

Common Function
  isValidEmail Function:
    A utility function to validate the email format using a regular expression.

Challenges Faced

Validation Logic Complexity:
  Ensuring that the validation logic for both forms was correctly implemented and handled edge cases.

Responsive Design:
  Ensuring that the form validation works seamlessly across different devices and screen sizes.

Error Message Placement:
  Properly positioning the error messages below the respective input fields without affecting the layout.
