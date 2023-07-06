# CSS Basic Project

This project is part of the CSS Basics curriculum and aims to help you practice and gain understanding of CSS concepts and techniques. The project focuses on creating a responsive web page layout using CSS Flexbox and applying basic styling.

![css](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/3/9530cfe68a62c19dbc5a1e32dfde651448b3d2e0.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230706%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230706T115728Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2ab4cca767e030ab3a8aa628b8929ad058fb1e9f47ea2973a8c4bea32e2d05c6)

## Project Badge

![Project Badge](https://img.shields.io/badge/CSS-Basic-brightgreen)

## Introduction

In this project, you will learn and apply the following concepts:

- What is CSS and how to add style to an element.
- Understanding classes and selectors.
- Computing CSS specificity value.
- Box properties in CSS.
- Understanding how a browser loads a webpage.

## Learning Objectives

By the end of this project, you should be able to explain the following topics without relying on external resources:

- What is CSS and how it enhances web page design.
- Adding style to HTML elements using CSS.
- Working with classes and selectors.
- Calculating CSS specificity value.
- Understanding box properties in CSS.
- Browser rendering process for loading webpages.

## Requirements

- All files should end with a new line.
- Include a README.md file at the root of the project folder.
- Use only HTML, CSS, and JavaScript. Do not install, import, or use external libraries.
- Ensure your code is W3C compliant and passes validation with W3C-Validator.

## Tasks

1. **Some early styling**
   - Copy the previously created `index.html` and `tweets.html` files into this folder.
   - Create an empty `styles.css` file.
   - Create the `base.css` file and add the provided content.
   - Add the following lines within the `<head>` tag of each HTML file:
     ```html
     <link href="base.css" rel="stylesheet">
     <link href="styles.css" rel="stylesheet">
     ```
   - Verify that your webpages now have an improved appearance after refreshing them in the browser.

2. **Positioning**
   - Implement a layout using CSS Flexbox to achieve the desired structure:
     ```
     Content of the <header> tag
     Content of the <article> tag    Content of the <aside> tag
     Content of the <footer> tag
     ```
   - Apply the necessary CSS code in the `styles.css` file to achieve the layout, following the provided steps.
   - Ensure that the content of `<article>` takes 2/3 of the page width, and `<aside>` takes 1/3 of the width.
   - Enable scrolling within `<article>` and `<aside>` using the `overflow-y: auto` property.
   - Verify that your layout matches the expected structure.

3. **Responsive web design**
   - Add the `class="works_on_smartphone"` attribute to the `<body>` tag in `index.html`.
   - Adjust the viewport settings in the HTML code to ensure proper rendering on smartphones.
   - Test your website on a smartphone to ensure it has a responsive layout.

4. **Some more styling**
   - Customize your website's appearance by adding additional CSS rules in the `styles.css` file.
   - You can modify colors, backgrounds, borders, and more.
   - Add a logo to the top-left of your page using a unicode character. Include the character as the first item in the list within the `<header>` tag, and apply the `logo` class to style it.

## Author

- Guillaume Salva, CTO at Holberton School

## Review

A manual QA review must be conducted after completing the project. Request a review from your peers or mentors to ensure the project meets the required objectives.

Feel free to provide additional information and context as needed in the README.md file. Good luck with your project!