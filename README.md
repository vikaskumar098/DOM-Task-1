
# 🧮 Simple Counter App

This is a simple and beginner-friendly **DOM Manipulation Project** using **HTML, CSS, and JavaScript**.
The app allows users to **increase or decrease** a number with smooth UI styling.

---

## 🚀 Features

* 🔼 Increment the counter
* 🔽 Decrement the counter
* 🎨 Clean & responsive UI
* ⚡ Lightweight and fast
* 🧠 Great for beginners learning DOM

---

## 📁 Project Structure

```
DOM-Task-1/
│── index.html
│── style.css
└── script.js
```

---

## 🖥️ Demo Screenshot

<img width="1914" height="722" alt="Screenshot 2025-11-15 022645" src="https://github.com/user-attachments/assets/fcacca30-e7cd-4d9e-8655-abe3428d0c0d" />


---

## 🧑‍💻 Code Explanation

### ✔ HTML

```html
<h1>Simple Counter</h1>
<h2>0</h2>
<button id="inc">Increment</button>
<button id="dec">Decrement</button>
```

### ✔ CSS

```css
button {
    padding: 10px 20px;
    font-size: 1.5rem;
    margin: 10px;
    cursor: pointer;
}
```

### ✔ JavaScript

```javascript
var inc = document.querySelector('#inc')
var dec = document.querySelector('#dec')
var h2 = document.querySelector('h2')

var a = 0

inc.addEventListener('click', function () {
    a++
    h2.innerHTML = a
})

dec.addEventListener('click', function () {
    a--
    h2.innerHTML = a
})
```

---

## 📦 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/vikaskumar098/DOM-Task-1.git
```

2. Open `index.html` in your browser
3. Click the buttons and enjoy! 🎉

---

## 🤝 Contributing

Pull requests are welcome.
Feel free to improve the UI or add new features like reset button, animations, etc.

---

## 🧑‍💼 About the Author

**Vikas Kumar**

LinkedIn: [linkedin.com/in/vikas0905](https://www.linkedin.com/in/vikas0905/)

---

## ⭐ Support

If you like this project,
**please ⭐ star the repo — it motivates me to do more!**

