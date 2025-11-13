# 🚀 Scroll to Top Button (Mini Project)

A clean, simple, and animated **Scroll to Top** button built using **HTML**, **CSS**, and **JavaScript**.  
When the user scrolls down the page, a floating button appears at the bottom-right corner.  
Clicking the button smoothly scrolls the page back to the top. ✨

---

## 🎯 Features

- 🖱️ **Auto Show/Hide Button** – appears when user scrolls down  
- ⚡ **Smooth Scroll Animation** – smooth scrolling effect on click  
- 💫 **Fade-in & Fade-out Animation** – for professional UI  
- 🎨 **Responsive Design** – works on desktop, tablet, and mobile  
- 🧠 **Simple Logic** – great for beginners learning DOM & events  

---

## 🧩 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure of the webpage |
| **CSS3** | Styling, animations, and layout |
| **JavaScript (ES6)** | Event handling and scroll functionality |

---

## 🧠 How It Works

1. When the user scrolls more than **300px**, the button appears using a CSS class (`.show`).  
2. When clicked, the page scrolls smoothly to the top using:
   ```js
   window.scrollTo({
     top: 0,
     behavior: "smooth"
   });
