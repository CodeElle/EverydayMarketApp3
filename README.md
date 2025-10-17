# Everyday Market App - Registration Form

This project is an Angular application featuring a comprehensive, template-driven registration form. It demonstrates a variety of form validation techniques, including built-in Angular validators, custom validator directives, and dynamic visual feedback for an enhanced user experience.

## Features

-   **Template-Driven Form**: A robust registration form built using Angular's template-driven approach with `ngModel`.
-   **Input Validation**: Each field has specific validation rules:
    -   **Full Name**: Required, minimum of 5 characters, and must contain only letters and spaces.
    -   **Email**: Required and must be in a valid email format.
    -   **Phone Number**: Required and must be a 10-digit number.
    -   **Date of Birth**: Required.
    -   **Street Address**: Required and can only contain letters, numbers, and spaces.
    -   **Province/Territory**: Required selection from a dropdown.
    -   **Country**: Required, and the user must select "Canada" to proceed.
    -   **Terms & Conditions**: The checkbox must be selected.
-   **Custom Validators**:
    -   `appPattern`: A reusable directive to validate an input against a given regular expression.
    -   `appRequiredValue`: A reusable directive to ensure a dropdown selection matches a specific required value (e.g., "Canada").
-   **Visual Feedback**: Form fields are dynamically styled with a red border if they are invalid and have been touched by the user.
-   **Submission Control**: The submit button is disabled until all form fields are valid.
-   **Routing**: Upon successful submission, the user is navigated from the registration page to the `/products` page.

## Technologies Used

-   Angular
-   TypeScript
-   HTML5
-   CSS

## Setup and Installation

1.  **Open the (unzipped) project folder**
    
2.  **Navigate to the project directory using the root terminal:**
    ```bash
    cd <project-directory>
    ```
3.  **Install NPM packages:**
    ```bash
    npm install
    ```
4.  **Run the application:**
    ```bash
    ng serve
    ```
    Navigate to `http://localhost:63121/`. The app will automatically reload if you change any of the source files.

## References
- Forms Validation: https://angular.dev/guide/forms
- Event Binding: https://v17.angular.io/guide/event-binding
- CSS Cheat Sheet: https://htmlcheatsheet.com/css/

### Project by - Laiza Mata ( October 2025)
