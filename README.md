# CSS Fundamentals Project

## Description

This project is a beginner-friendly static website built using only **HTML**, **CSS**, and **JavaScript**, with no external libraries or frameworks (such as Bootstrap, React, or Vue.js). The goal is to demonstrate a solid understanding of how CSS works, how styles are applied to HTML elements, and how CSS specificity affects style resolution.

All code is W3C compliant and passes W3C validation.

---

## Learning Objectives

By completing this project, I am able to explain the following concepts without external help:

### ✅ General

- **What is CSS:**  
  CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of HTML elements — how they look, rather than what they mean.

- **How to add style to an element:**  
  Styles can be added:
  - Inline, using the `style` attribute.
  - Internally, using a `<style>` tag in the HTML `<head>`.
  - Externally, by linking a `.css` file using `<link>` in the HTML `<head>`.

- **What is a class:**  
  A class is a reusable identifier assigned to HTML elements to apply specific CSS rules. Classes are declared using a period (`.`) followed by the class name in CSS.

- **What is a selector:**  
  Selectors target HTML elements in order to apply styles to them. Examples: element selectors (`p`), class selectors (`.my-class`), ID selectors (`#my-id`), attribute selectors, and pseudo-selectors.

- **How to compute CSS Specificity Value:**  
  CSS specificity determines which rule applies when multiple rules target the same element. It's calculated as:
    - Inline styles: `1000`
    - ID selectors: `0100`
    - Class, attribute, and pseudo-class selectors: `0010`
    - Element and pseudo-element selectors: `0001`

- **What are Box properties in CSS:**  
  Every element is a rectangular box and has properties like:
    - `margin`: space outside the border
    - `border`: the edge of the box
    - `padding`: space inside the border, around the content
    - `width` / `height`: content dimensions

- **How does the browser load a webpage:**  
  1. The browser sends an HTTP request to the server.
  2. The server returns HTML.
  3. The browser parses the HTML, downloading and applying CSS and JavaScript as needed.
  4. The CSS is applied using the **Cascade**, **Inheritance**, and **Specificity**.
  5. The DOM and CSSOM are built and rendered.

---

## Project Requirements

- ✅ All files end with a new line.
- ✅ `README.md` file included at the root of the project.
- ✅ No external libraries or frameworks are used.
- ✅ Website built using only HTML, CSS, and JavaScript.
- ✅ All code validates with W3C Validator.

