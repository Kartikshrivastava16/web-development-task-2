# Task 2 — Intermediate HTML, CSS & JavaScript

**ApexPlanet Software Pvt Ltd · Internship Project**

A four-step project focused on enhancing HTML and CSS skills and learning JavaScript for DOM manipulation. Each step is a standalone HTML file demonstrating a specific concept.

---

## Project Structure

```
task 2/
├── index.html              # Project hub — links to all four tasks
├── contact-form.html       # Step 1 · Contact Form
├── form-validation.html    # Step 2 · JS Form Validation
├── responsive-layout.html  # Step 3 · Responsive Layout
├── todo-list.html          # Step 4 · Dynamic To-Do List
└── README.md               # This file
```

---

## Steps

### Step 1 · Contact Form (`contact-form.html`)

**Objective:** Build forms with various input fields and style them with CSS.

- Input types used: `text`, `email`, `tel`, `select`, `textarea`, and a submit button
- Two-column name row using CSS Flexbox
- Styled with a teal card design, focus ring colour change, and a success banner on submit
- Fully responsive card layout

---

### Step 2 · JS Form Validation (`form-validation.html`)

**Objective:** Use JavaScript to ensure form data is valid.

- Validates all required fields on submit
- Email format checked with regex: `/^[^\s@]+@[^\s@]+\.[^\s@]+$/`
- Indian 10-digit phone number checked with regex: `/^[6-9]\d{9}$/`
- Password strength meter (Weak / Fair / Good / Strong) based on length, uppercase, digits, and symbols
- Confirm-password match check
- Terms & Conditions checkbox validation
- Green/red border feedback on each field via `.valid` / `.error` CSS classes

---

### Step 3 · Responsive Layout (`responsive-layout.html`)

**Objective:** Build layouts that adapt to different screen sizes.

- **Flexbox** used for the sticky navigation bar (`justify-content: space-between`)
- **CSS Grid** used for the main content area (3 columns: sidebar · articles · widgets)
- **Media queries** at two breakpoints:
  - `≤ 900px` — collapses to 2-column layout
  - `≤ 640px` — collapses to single-column; hamburger menu appears
- CSS custom properties (`--teal`, `--teal-dark`, `--teal-light`) for consistent theming
- Semantic HTML elements: `<nav>`, `<aside>`, `<main>`, `<article>`, `<footer>`
- Hamburger menu toggle implemented with JavaScript

---

### Step 4 · Dynamic To-Do List (`todo-list.html`)

**Objective:** Learn DOM manipulation with JavaScript.

- Add tasks by clicking **+ Add** or pressing **Enter**
- Set task priority: High / Medium / Low (colour-coded badges)
- Mark tasks as complete with a checkbox; completed tasks show a strikethrough
- Delete individual tasks with the ✕ button
- Three filter tabs: **All**, **Active**, **Completed**
- **Clear completed** button removes all done tasks at once
- Live done/remaining counter
- `escHtml()` helper sanitises input to prevent XSS
- CSS `@keyframes slideIn` animation on new task items
- Seed tasks pre-loaded on first render

---

## Technologies Used

| Technology | Where used |
|---|---|
| HTML5 (semantic elements) | All files |
| CSS Flexbox | Navigation bar, form rows |
| CSS Grid | Index dashboard, responsive layout |
| CSS Media Queries | Responsive layout breakpoints |
| CSS Custom Properties | Theming across all files |
| Vanilla JavaScript | Form validation, DOM manipulation, hamburger menu |
| Regex | Email and phone validation |

---

## How to Run

No build tools or dependencies required. Open any file directly in a browser:

```
index.html   ←  start here
```

Or open individual task files directly. All files are self-contained with inline CSS and JavaScript.

---

## Author

**Kartik** · ApexPlanet Software Pvt Ltd Internship
