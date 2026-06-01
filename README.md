# Web Calculator

A simple, responsive web calculator built as part of my frontend development learning journey, with a primary focus on **JavaScript**. This project allowed me to practically apply programming logic, handle data types, and manage event listeners.

---

## Features

*   **Basic Mathematical Operations:** Addition, subtraction, multiplication, and division.
*   **Floating-point Numbers:** Support for decimal calculations.
*   **Reset Functionality (C / AC):** Clear the current entry or reset the entire calculator state.
*   **Backspace Support:** Easily delete the last entered digit to correct mistakes.
*   **Responsive Design:** Fully optimized to look and work great on both mobile and desktop screens.

---

## Technologies Used

This project was built using the classic web development trio:

1.  **HTML5** – For the semantic structure of the calculator (buttons, display grid).
2.  **CSS3** – For styling the layout (utilizing Flexbox/Grid) and adding smooth hover effects.
3.  **Vanilla JavaScript (ES6+)** – For the entire business logic, which was the main focus of this project.

---

## What I Learned (Focus on JavaScript)

This project served as an excellent sandbox for strengthening my core programming skills. By focusing deeply on JavaScript, I learned how to:
*   **Handle Events Efficiently:** Instead of attaching separate event listeners to every single button, I explored efficient event management (like Event Delegation).
*   **Manage Data Types & Strings:** Converting inputs using `parseInt` and `parseFloat`, and sanitizing user input (e.g., preventing multiple decimals in a single number).
*   **State Management:** Keeping track of the calculator's current memory, active operator, and updating the UI display dynamically.
*   **Avoid Bad Practices (`eval()`):** The calculation logic is built using clean, conditional functions rather than relying on `eval()`, ensuring better security and coding practices.
