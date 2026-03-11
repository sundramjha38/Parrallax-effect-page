# Parallax / Traverse Effect Web Page 🌐

This project is a simple web page created to **practice and understand CSS positioning concepts** in depth.  
While building this page, I explored how elements move and stack on the screen using different CSS properties.

---

## 📸 Demo


![Demo](demo.gif)

---

## 🚀 What I Learned

This project helped me gain hands-on experience with:

- **CSS Position Property** — `static`, `relative`, `absolute`, `fixed`, `sticky`
- **Z-Index & Stacking Context** — how elements overlap and common z-index mistakes
- **Parallax / Traverse Effect** — creating depth using `perspective`, `translateZ`, and `transform-style: preserve-3d`
- **Background Attachment Fixed** — achieving a scrolling parallax effect on section images
- **Layout & Debugging Skills** — inspecting elements, fixing overlap issues

---

## 🛠️ Tech Used

- HTML5
- CSS3

---

## 📁 Project Structure

```
├── index.html
├── index.css
├── background.png
├── foreground.png
├── sport-1.jpg
├── sport-2.jpg
└── sport-3.jpg
```

---

## ⚙️ How It Works

- The `.warraper` has `perspective: 10px` which creates a 3D space for child elements.
- `.background` and `.foreground` images are pushed back on the Z-axis using `translateZ` and scaled up to fill the screen — this creates the parallax depth effect.
- Section background images use `background-attachment: fixed` to create a second layer of parallax as the user scrolls.

---

## 🏃 How to Run

Open `index.html` directly in any browser. No setup needed.

---

## 📌 Note

> `background-attachment: fixed` may not work on some mobile browsers due to rendering limitations.