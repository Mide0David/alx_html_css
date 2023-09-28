# HTML Forms Project

![Project Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Start Date](https://img.shields.io/badge/Start%20Date-Sep%2022%2C%202023%2010%3A00%20PM-brightgreen)
![End Date](https://img.shields.io/badge/End%20Date-Sep%2028%2C%202023%209%3A59%20PM-red)
![Manual QA Review](https://img.shields.io/badge/Manual%20QA%20Review-Required-orange)

**By: Dr. Ehoneah Obed**

## Table of Contents
- [Description](#description)
- [Resources](#resources)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Tasks](#tasks)

## Description
This project is focused on creating HTML forms with various specifications and implementing HTML5 validation attributes. The forms include a simple contact form, a registration form, a subscription form with radio buttons, a feedback form with checkboxes and file upload, and a survey form with select dropdown, time, and date selection.

## Resources
Before starting this project, you may find it helpful to review the following resources:
- [Your first form](link-to-resource)
- [How to structure a web form](link-to-resource)
- [Basic Native form controls](link-to-resource)
- [The HTML5 input types](link-to-resource)
- [Other form controls](link-to-resource)

## Learning Objectives
Upon completion of this project, you should be able to:
- Explain what HTML forms are.
- Demonstrate knowledge of HTML form elements and their attributes (e.g., input, radio buttons, checkboxes, dropdowns).
- Implement basic form validation using HTML5 attributes such as `required`, `minlength`, `maxlength`, `pattern`, and more.

## Requirements
**General**
- Recommended code editor: Visual Studio Code
- All your files should end with a new line.
- A `README.md` file, at the root of the project folder, is mandatory.
- You are not allowed to install, import, or use external libraries. This website must be built with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
- Your code should be W3C compliant and validate with W3C-Validator.

## Tasks
### 0. Simple Contact Form
- Create an HTML form for a basic contact form with the following requirements:
  - Include fields for the user’s name, email address, and message.
  - Apply appropriate HTML5 validation attributes to ensure the name and email fields are required and that the email field accepts a valid email format.
  - Use a `<textarea>` element for the message field to allow for a long description and not limit it to just one line.
  - Add a submit button to submit the form.
- **Repo:**
  - GitHub repository: [alx_html_css](link-to-repo)
  - Directory: `html_forms`
  - File: `0-contact-form.html`

### 1. Registration Form
- Design an HTML registration form with the following specifications:
  - Include fields for the user’s name, email, password, and confirm password.
  - Implement HTML5 validation attributes to ensure all fields are required, and the email field accepts a valid email format, and the password fields match.
  - Use appropriate input types (e.g., email, password) and labels for each field.
- **Repo:**
  - GitHub repository: [alx_html_css](link-to-repo)
  - Directory: `html_forms`
  - File: `1-registration-form.html`

### 2. Subscription Form with Radio Buttons
- Build an HTML form for a subscription with the following criteria:
  - Include fields for the user’s name, email, and subscription preference (monthly, yearly).
  - Utilize radio buttons for the subscription preference and ensure that the user can only select one option.
  - Apply HTML5 validation to ensure all fields are required, and the email field accepts a valid email format.
- **Repo:**
  - GitHub repository: [alx_html_css](link-to-repo)
  - Directory: `html_forms`
  - File: `2-subscription-form.html`

### 3. Feedback Form with Checkboxes and File Upload
- Develop an HTML feedback form with checkboxes to capture user opinions and the ability to upload a file:
  - Include fields for the user’s name, email, checkboxes for various feedback options (e.g., excellent, good, average, poor), and a file upload field.
  - Ensure that the user can select multiple checkboxes.
  - Specify the file upload field using the `<input type="file">` element.
  - Implement HTML5 validation to ensure the name, email, at least one checkbox, and a file are filled out.
- **Repo:**
  - GitHub repository: [alx_html_css](link-to-repo)
  - Directory: `html_forms`
  - File: `3-feedback-form.html`

### 4. Survey Form with Select Dropdown, Time, and Date Selection
- Design an HTML survey form with a select dropdown to collect user preferences, along with time and date selection:
  - Include fields for the user’s name, email, a select dropdown for their favorite color (options: red, blue, green), and separate fields for time and date selection.
  - Apply HTML5 validation to ensure all fields are required, including the select dropdown, time, and date fields.
  - To implement the time and date selection, use the following input types:
    - For time: `<input type="time">`
    - For date: `<input type="date">`
- **Repo:**
  - GitHub repository: [alx_html_css](link-to-repo)
  - Directory: `html_forms`
  - File: `4-survey-form.html`

---

