# Multiplication App

An interactive web-based **Multiplication Quiz App** built with HTML, CSS, and vanilla JavaScript. It generates random single-digit multiplication problems, validates user answers on form submission, and persists the player's score across sessions using the browser's `localStorage`.

## Features

* **Random Question Generator:** Dynamically creates new multiplication questions using numbers between `1` and `10` on every round.
* **Real-Time Score Tracking:** Awards `+1` point for every correct answer and deducts `1` point for incorrect answers.
* **Persistent Score with Local Storage:** Saves the current score in `localStorage` so progress remains intact even after refreshing or closing the browser.
* **Clean, Centered Card UI:** Features a bold purple backdrop with a high-contrast white quiz card, oversized centered input field, and responsive hover effects.

## Built With

* **HTML5** – Semantic form structure for displaying the score, question prompt, number input, and submit button.
* **CSS3** – Flexbox centering, card drop shadows, custom input borders, and brightness hover transitions.
* **JavaScript (ES6)** – Random number generation (`Math.random()`, `Math.ceil()`), form event handling, DOM manipulation, and `localStorage` persistence.

## Project Structure

```text
multiplication-app/
├── index.html      # Main HTML quiz structure
├── style.css       # Card layout, typography, and button styling
└── script.js       # Question logic, answer validation, and score storage
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com
   ```
2. **Navigate to the project folder**
   ```bash
   cd multiplication-app
   ```
3. **Run the project**
   Open `index.html` directly in any web browser. No installations or build tools are required.

## Future Improvements

* Add a **Reset Score** button so players can restart their score from `0` at any time.
* Display instant visual feedback (e.g., green or red flash) before loading the next question.
* Fix the variable typo on line 13 of `script.js` (`socre = 0;` to `score = 0;`) so initial scores always display `0` instead of `null`.
