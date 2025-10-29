# Bouncing Ball Animation

A smooth, realistic bouncing ball animation built using **pure HTML and CSS**. This project demonstrates CSS animations, transformations, and keyframes to create lifelike motion and depth — all without JavaScript.

---

## 🎬 Preview

The animation showcases a bright, gradient-colored ball bouncing with squash-and-stretch physics and a soft shadow that reacts to its height.
---

## 📁 Project Structure

```
project-folder/
├── index.html   # Main HTML file containing markup and embedded CSS
├── README.md    # Project documentation (this file)
```

---

## ⚙️ How It Works

* The **ball** element uses CSS keyframes (`@keyframes bounce`) to move up and down smoothly.
* A **shadow** element scales and fades dynamically to simulate realistic lighting.
* The **floor** adds depth and defines the surface.
* All motion is driven by CSS transitions and `cubic-bezier()` easing for smooth realism.

---

## 🧩 Features

✅ 100% CSS-only — no JavaScript required
✅ Squash and stretch animation for realism
✅ Responsive and scalable for any screen
✅ Customizable colors, sizes, and bounce height

---

## 🪄 Customization

You can tweak the look and feel by modifying CSS variables at the top of the `<style>` section in `index.html`:

```css
:root {
  --ball-size: 100px;           /* Size of the ball */
  --bounce-height: 250px;       /* How high it bounces */
  --bounce-speed: 1.2s;         /* Speed of one bounce cycle */
  --ball-gradient: radial-gradient(circle at 30% 30%, #ffed4a, #facc15, #eab308);
}
```

---

## 🚀 Running the Project

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Enjoy the animation!

---

## 💡 Ideas for Enhancement

* Add multiple balls with random bounce timing.
* Include a rainbow gradient or glowing trail effect.
* Use JavaScript for interactivity (click to bounce, drag, etc.).

---

## 🧠 Learning Highlights

* CSS keyframes & easing curves
* Transform origin, scale, and translation
* Layered elements for depth illusion

---

**Made with ❤️ using HTML & CSS**