
- Name: Morufat Lamidi Alade
- Submission Requirement: GitHub link with answers
- Deadline: 11:59 PM

## Table of Contents

1. [AltSchool Student Portal & Biography](#student-portal)
2. [Project Overview](#overview)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Get In Touch](#get-in-touch)
6. [File Structure](#file-structure)


# AltSchool Student Portal & Biography

A semantic HTML project built for the AltSchool Africa School of Engineering (AI-Powered Full-Stack Engineering Track). 

This repository contains the structural foundation (HTML only) for a personal biography page and an AltSchool application form.

## Project Overview

This project demonstrates the use of semantic HTML5 to create accessible, well-structured, and meaningful web pages without relying on CSS for layout or styling. 

The project consists of two main pages:
1. **Biography Page** (`index.html`): A personal introduction, goals, and technical skills overview.
2. **Application Form** (`form.html`): A secure sign-in/application portal for the AltSchool Student Portal.

## Features

### Biography Page (`index.html`)
- **Semantic Structure:** Utilizes `<header>`, `<nav>`, `<main>`, `<section>`, `<details>`, and `<footer>` tags to define the document outline.
- **Internal Navigation:** A "Table of Contents" using anchor links (`#about-me`, `#goals`, etc.) for smooth in-page navigation.
- **Accessible Navigation:** Main navigation links to the Home page and the Application Form.
- **Collapsible Content:** Uses the `<details>` and `<summary>` tags for a native, accessible accordion to view technical skills.
- **External Links:** Secure external linking to LinkedIn and GitHub with `target="_blank"` and `rel="noopener noreferrer"` for security.
- **Back to Top:** A floating link to return to the top of the page.

### Application Form Page (`form.html`)
- **Authentication Toggle:** A navigation area to switch between "Sign up" and "Sign in" states.
- **Semantic Form Structure:** Uses `<form>`, `<label>`, and `<input>` elements with appropriate `type`, `id`, `name`, and `autocomplete` attributes for browser autofill support.
- **Accessibility:** Includes `aria-label` and `aria-current` attributes to ensure screen reader compatibility.
- **Password Visibility Toggle:** A button to toggle password visibility (with an SVG eye icon).
- **Primary & Secondary Actions:** Includes a primary submit button ("Proceed to Dashboard") and a secondary Google login option.
- **Chat Widget:** A floating chat button (SVG) in the bottom right corner.

## Technologies Used

- **HTML5:** For semantic structure, accessibility, and form handling.
- **SVGs (Inline):** For scalable icons (Eye icon, Google logo, Chat bubble, Arrow).

## Get in Touch

You can reach out to me;

- Linkedin- [Morufat-Lamidi](https://linkedin.com/in/morufat-lamidi)
- Frontend Mentor - [@Ehmkayel](https://www.frontendmentor.io/profile/Ehmkayel)
- Twitter - [@kamalehmk](https://www.twitter.com/kamalehmk)
- Gmail- [Mail](mailto:workwithehmkay@gmail.com);

## File Structure

```text
├── index.html       # The personal biography page
├── form.html        # The AltSchool application/sign-in form
└── README.md        # Project documentation

