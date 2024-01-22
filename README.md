# Form

This project is a simple sign-up form for BKT48. It is built with HTML, CSS, and JavaScript.

## Features

- User can enter their name, email, and password.
- User can choose their favorite member (oshi) from Yori, Ara, and Chika.
- User can select the amount for top-up point.
- User can write a message in the textarea.
- After clicking the 'proses' button, an alert will show up displaying the user's input.

## Code Explanation

The HTML structure includes a form with various input fields. The CSS in the head section styles the form and the input fields. The JavaScript function `handleSubmit()` is triggered when the form is submitted. This function prevents the form from being submitted in the default way using `event.preventDefault()`, and then gathers the values from the input fields. These values are displayed in an alert.

## Usage

To use this form, simply open the HTML file in a web browser. Fill out the form and click the 'proses' button to see the result.

## Note

This is a basic example and might need to be adjusted to meet your needs, especially in terms of validation and sanitization of user input to prevent attacks such as Cross-Site Scripting (XSS). This code should be run in a secure environment.
