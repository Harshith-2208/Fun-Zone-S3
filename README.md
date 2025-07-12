# Fun-Zone
## Build Your Own "Draw a Perfect Circle" Game — Inspired by [neal.fun](https://neal.fun/perfect-circle)

## Project Description
Recreate a web-based game where users attempt to draw a perfect circle — using nothing but HTML, CSS, and JavaScript. In this task, you’ll build a browser-based game that challenges the user to draw a circle around a **fixed central point**. The game should evaluate how close the drawing is to a mathematically perfect circle and display a score.

The overview of the project:

- Drawing on HTML Canvas
- Handling mouse events (`mousedown`, `mousemove`, `mouseup`)
- Implementing geometric calculations (distance, variance)
- Using session storage
- Audio integration, UI polish, scoring feedback

---

## Requirements

### Functional Features
- A canvas that users can draw on using the mouse.
- A **fixed red dot** at the center of the canvas.
- User can draw a freehand loop using `mousedown`, `mousemove`, `mouseup`.
- When the mouse is released:
  - The app evaluates how circular the drawing is.
  - Score is calculated and shown.
- Only calculate this **if the center point lies inside the drawn path**. Otherwise, show an error like:
  **The red dot is not inside your circle!**
- Store and display the **best score during the session**.
- Add a sound effect that plays while drawing.
- Offer a clear/reset button to try again.
- Add selectable modes like:
  - Easy: Large center dot, generous scoring.
  - Medium: Normal scoring, normal center.
  - Hardcore: Small center dot, high accuracy needed, no real-time hints.
- Time-based Bonus - The one who completes faster gets more score.
- Add a toggle for dark mode or light mode. 

---

## Reference

You can play the original inspiration here:  
🔗 https://neal.fun/perfect-circle/

You're encouraged to try it out to understand the user experience, but **do not copy the code** — build it from scratch yourself.

---

## Tech Stack

- **HTML** – structure
- **CSS** – styling the layout and canvas
- **JavaScript** – all game logic and scoring
- **Canvas API** – to handle freehand drawing
- **Audio** tag for sound effects
- **sessionStorage** for best score tracking

---



