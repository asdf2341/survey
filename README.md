# 📋 Survey Form

A **Survey Form** is a simple web application that collects user information and feedback. This project is built as part of a learning exercise and fulfills a set of user stories, providing a functional and user-friendly form. The project is **responsive**, **HTML5-compliant**, and features **form validation**.

## 📝 Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [User Stories](#user-stories)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## 🌐 Live Demo

Check out the live demo of the app: [Survey Form](https://your-live-demo-link.com)

## ✨ Features

- Responsive design for desktop and mobile devices.
- HTML5 validation for email and number input fields.
- Includes dropdowns, radio buttons, checkboxes, and a text area for feedback.
- User-friendly labels and placeholder text for guidance.
- Submit button to collect and process the form data.

## ✅ User Stories

The project fulfills the following user stories:

1. The page has a title in an `h1` element with an `id` of `title`.
2. A short explanation is provided in a `p` element with an `id` of `description`.
3. The form element has an `id` of `survey-form`.
4. The form includes:
   - A text input field for the user's name with `id="name"`.
   - An email input field with `id="email"`, which shows a validation error for incorrect formats.
   - A number input field with `id="number"` that accepts only numerical values.
5. Labels for the name, email, and number input fields are provided with the following IDs:
   - `id="name-label"`
   - `id="email-label"`
   - `id="number-label"`
6. Placeholder text is included for the name, email, and number input fields for additional guidance.
7. A dropdown element with an `id` of `dropdown` and at least two options.
8. At least two radio buttons grouped by the `name` attribute for user selection.
9. A series of checkboxes, each with a `value` attribute for multiple selections.
10. A `textarea` element for additional comments or feedback.
11. A submit button with an `id` of `submit` to send the form data.

## 💻 Technologies Used

- HTML
- CSS

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/survey-form.git
   ```
2. Navigate to the project folder:
   ```bash
   cd survey-form
   ```
3. Open `index.html` in your browser to view the form.

## 📚 Usage

1. Open the form in your browser.
2. Fill out the required fields:
   - Enter your name, email, and age.
   - Choose an option from the dropdown menu.
   - Select a radio button for a specific question.
   - Mark any relevant checkboxes.
   - Provide additional comments in the textarea.
3. Click the **Submit** button to send your response.

## 📁 Project Structure

```
survey-form/
├── index.html       # Main HTML file
├── styles.css       # CSS for styling
├── README.md        # Project documentation
```

### `index.html`

Contains the HTML structure of the form, including input fields, labels, and buttons.

### `styles.css`

Includes the CSS for styling the form, making it responsive and visually appealing.

## 🛠️ HTML5 Form Validation

- The email input field uses built-in HTML5 validation to ensure correct email format.
- The number input field has `min` and `max` attributes to limit the range of values.
- The form uses `required` attributes to ensure that necessary fields are filled out.

## 💡 Personal Style

The form has a simple, clean, and user-friendly design. It features a responsive layout, intuitive labels, and consistent spacing for an optimal user experience.



---
