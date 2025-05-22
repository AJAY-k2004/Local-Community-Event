# 🌐 Local Community Event Portal

This project is a lightweight, browser-based portal designed to help residents register for community events, check locations, and access basic services. Built entirely with HTML5, CSS, and JavaScript, it serves as a hands-on exercise to explore modern web development features.

---


---

## 🔧 Features Implemented

### ✅ 1. HTML5 Base Template
- Semantic tags like `<header>`, `<nav>`, `<main>`, and `<footer>`
- UTF-8 charset, `lang="en"` for compatibility

### ✅ 2. Navigation
- Navigation bar with internal anchors (`#events`, `#contact`)
- Link to external help document using `target="_blank"`

### ✅ 3. Welcome Banner
- Unique styling using `id`, `class`, and inline styles
- Includes a `div` with a promotional message

### ✅ 4. Image Gallery
- Table layout with 2 rows × 3 columns of community event images
- Uses `alt`, `title`, and CSS borders

### ✅ 5. Event Registration Form
- Includes inputs: name, email, date, event type, message
- Validates using HTML5 attributes (`required`, `autofocus`, `placeholder`)
- Displays confirmation using `<output>`

### ✅ 6. Feedback and Event Handling
- Validates phone number with `onblur`
- Shows fee based on dropdown using `onchange`
- Confirmation on `onclick`
- Enlarges image on `ondblclick`
- Tracks feedback character count via `onkeyup`

### ✅ 7. Promo Video
- `<video>` element with `controls` and `oncanplay` event
- Warns users on leaving the page using `onbeforeunload`

### ✅ 8. User Preferences
- Saves preferred event type using `localStorage`
- Restores preference on reload
- Button to clear `localStorage` and `sessionStorage`

### ✅ 9. Geolocation
- Uses `navigator.geolocation.getCurrentPosition`
- Handles permissions, errors, and timeout
- Displays user’s coordinates

### ✅ 10. Debugging with DevTools
- Live style editing using Inspect Element
- Logs and error tracking via Console
- JS breakpoints and variable watches via Sources tab

---

## 💻 Requirements

- Any modern browser (Google Chrome recommended)
- Local file server or open `index.html` directly

---



## 🙌 Acknowledgements

- HTML5 & CSS3 documentation (MDN Web Docs)
- Chrome DevTools for debugging
- JavaScript Event handling basics


