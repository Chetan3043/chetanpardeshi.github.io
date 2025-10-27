# 🎨 Random Color Generator

This is a simple web application that generates a **random color** each time you click the **"Generate Color"** button.  
The RGB color value is displayed on the screen, and the background color updates instantly.

---

## Features
- Generates random RGB color values.
- Displays the generated color in real time.
- Simple and clean UI.
- Built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks required.

---

## How It Works
1. When you click the **Generate Color** button, a random RGB color is generated using JavaScript.
2. The RGB value is displayed in the heading (`<h3>`).
3. The background of the `<div>` element changes to the generated color.

```js
function getRandomColor() {
  let red = Math.floor(Math.random() * 255);
  let green = Math.floor(Math.random() * 255);
  let blue = Math.floor(Math.random() * 255);
  return `rgb(${red}, ${green}, ${blue})`;
}
