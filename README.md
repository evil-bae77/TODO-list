# 📝 Simple To-Do List (JavaScript)

A beginner-friendly **To-Do List web app** built using **HTML, CSS (optional), and Vanilla JavaScript**. This project allows users to add and delete tasks dynamically.

---

## 🚀 Features

* ➕ Add new tasks
* ❌ Delete existing tasks
* ⚡ Instant DOM updates (no page reload)
* 🧠 Beginner-friendly logic using pure JavaScript

---

## 🛠️ Technologies Used

* HTML
* JavaScript (DOM Manipulation)

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
└── README.md
```

---

## 💻 How It Works

1. User enters a task in the input field.
2. Clicks the **ADD** button.
3. A new `<li>` element is created dynamically.
4. Each task includes a **DELETE** button.
5. Clicking DELETE removes the specific task.

---

## 📜 Code Explanation

### 🔹 Adding a Task

* A new `<li>` element is created using:

```javascript
var lstitm = document.createElement("li")
```

* The input value is inserted along with a delete button:

```javascript
lstitm.innerHTML = inpt.value + "<button onclick='dlt(event)'>DELETE</button>"
```

* The item is appended to the `<ul>`:

```javascript
ul.insertAdjacentElement("beforeend", lstitm)
```

---

### 🔹 Deleting a Task

* The delete button triggers the `dlt()` function:

```javascript
function dlt(event) {
    event.target.parentElement.remove()
}
```

* It removes the parent `<li>` of the clicked button.

---





## ▶️ How to Run

1. Create a file named `index.html`
2. Paste your code inside it
3. Open the file in your browser

---

## 🎯 Future Improvements

* ✏️ Edit tasks
* 💾 Save tasks using Local Storage
* 🎨 Add CSS styling
* 📱 Make it responsive
* ✅ Mark tasks as completed

---

## 🙌 Conclusion

This is a simple and effective project to understand:

* DOM manipulation
* Event handling
* Dynamic UI updates

Perfect for beginners starting with JavaScript 🚀

---
