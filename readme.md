# 🧮 Simple Calculator Web App

A clean, responsive, and interactive calculator built using **HTML, CSS, and Vanilla JavaScript**.  
This project demonstrates DOM manipulation, event handling, and dynamic UI updates in a simple and beginner-friendly way.

## 🚀 Features

- Perform basic arithmetic operations (+, −, ×, ÷)
- Real-time display updates
- Clear (`C`) button
- Backspace (`←`) functionality
- Error handling for invalid expressions
- Responsive and modern UI
- External JavaScript structure

 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## 📂 Project Structure

project-folder/
│
├── index.html
├── style4.css
├── first_project.js
└── README.md

## ⚙️ How It Works

- All calculator buttons are selected using `querySelectorAll()`.
- Each button listens for a `click` event.
- When clicked:
  - Numbers/operators are appended to the display.
  - `C` clears the screen.
  - `←` removes the last character.
  - `=` evaluates the expression using `eval()`.
- Errors are handled safely using `try...catch`.


## ▶️ How to Run

1. Download or clone the repository.
2. Open `index.html` in any modern browser.
3. Start calculating 🎉

No installations required.

## 📚 Learning Objectives

This project helps you understand:

- DOM selection and manipulation
- Event listeners
- Arrow functions
- Conditional logic
- String methods (`slice()`)
- Basic error handling in JavaScript


## ⚠️ Note

This project uses `eval()` for expression evaluation.  
While acceptable for learning purposes, it is **not recommended for production applications** due to security considerations.


## 🌟 Future Improvements

- Keyboard support  
- Scientific calculator functions  
- Dark/Light mode toggle  
- Calculation history  
- Replace `eval()` with a safer parser  


**Built for learning and practice.**