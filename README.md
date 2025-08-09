# Ouija Board Web Project

A simple interactive Ouija board web app with a spooky atmosphere and basic spirit communication simulation.

---

## Overview

This project consists of two main HTML pages:

- **welcome.html** — A landing page with a haunting invitation and a link to start the Ouija board experience.
- **last.html** — The interactive Ouija board interface that simulates spirit communication by spelling out answers.

---

## Features

### welcome.html
- Full-screen background image (`cover.jpeg`) with a spooky vibe.
- Large heading prompting the user to start the game.
- A styled button that navigates to the Ouija board page (`last.html`).

### last.html
- Full-screen background image (`oja.jpeg`) with a fixed cover style.
- A visually styled Ouija board including:
  - Three rows of letters (A-Z),
  - Number row (0-9),
  - YES and NO options,
  - A "GOODBYE" section.
- A translucent planchette (circle) that moves smoothly over letters and numbers.
- Input box for users to type questions.
- Button to "Ask" the question.
- Predefined responses for specific questions and a default spooky answer for unknown queries.
- The planchette spells out the answer by moving over each character on the board with a smooth animation.

---

## How to Use

1. Place both `welcome.html` and `last.html` in the same folder.
2. Make sure the image files `cover.jpeg` (for welcome page) and `oja.jpeg` (for Ouija board background) are also placed in the same folder.
3. Open `welcome.html` in a modern web browser.
4. Click the **Go👉🏻** button to navigate to the Ouija board.
5. Type a question into the input box and click **Ask**.
6. Watch the planchette move over letters/numbers to spell the response below the board.

---

## File Structure


/ (project root)
|-- welcome.html
|-- last.html
|-- cover.jpeg (background image for welcome page)
|-- oja.jpeg (background image for Ouija board page)

---

## Code Highlights

- CSS Flexbox is used extensively for layout and centering.
- The Ouija board uses semi-transparent backgrounds and stylized text for a mystical effect.
- The planchette position is controlled by JavaScript to visually "spell" out answers letter by letter.
- Predefined answers are stored in a JavaScript object for easy expansion.
- Smooth CSS transitions make the planchette movement visually appealing.

---

## Customization

- Replace `cover.jpeg` and `oja.jpeg` with your own images to change the atmosphere.
- Add more predefined questions and answers in the `specialAnswers` JavaScript object inside `last.html`.
- Adjust styling in the CSS sections to change colors, fonts, sizes, or layout.

---

## Browser Compatibility

Tested on modern browsers (Chrome, Firefox, Edge). Requires JavaScript enabled for full functionality.

---

## License

Feel free to use and modify this project for educational and personal use.
