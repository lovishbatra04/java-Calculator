# java-Calculator
A simple calculator built using HTML, CSS, and JavaScript that performs basic arithmetic operations like addition, subtraction, multiplication, and division.
# 🧮 Calculator Web App

A simple and clean calculator web application built using **HTML, CSS, and JavaScript**.  
This project performs basic arithmetic operations with a user-friendly interface.

---

## 🚀 Features

- Addition (+)
- Subtraction (-)
- Multiplication (×)
- Division (÷)
- Clean and responsive UI
- Instant calculation using JavaScript

---

## 🛠️ Tech Stack

- HTML5 – Structure of the calculator
- CSS3 – Styling and layout design
- JavaScript – Logic and functionality

---

## 📂 Project Structure
- index.html [index.html](https://github.com/user-attachments/files/28946174/index.html)
- style [style.css](https://github.com/user-attachments/files/28946159/style.css)
- script.js [script.js](https://github.com/user-attachments/files/28946137/script.js)
---

## 💡 How It Works

- User clicks number buttons
- Expression is shown on screen
- When "=" is pressed, JavaScript evaluates the expression
- Result is displayed instantly

---

## ▶️ How to Run

1. Download or clone this repository
2. Open `index.html` in any browser
3. Start using the calculator

---


## 👨‍💻 Author

**Lovish**  
Aspiring Full Stack Developer  
Focused on building real-world frontend projectsfunction addValue (value) {[Uploading style.css…]()

    let display = document.getElementById("display");
    display.value += value
}

function calculate () {
    let display = document.getElementById("display"); body {
            text-align: center;
            font-family: Arial;
            margin-top: 50px;
        }

        input {
            width: 220px;
            height: 40px;
            font-size: 20px;
            text-align: right;
            margin-bottom: 10px;
        }

        button {
            width: 50px;
            height: 50px;
            font-size: 18px;
            margin: 5px;
            cursor: pointer;
        }
    display.value = eval(display.value);
}

function clearDisplay () {
    document.getElementById("display").value = "";
}

---

## 📌 Future Improvements

- Add keyboard support
- Add dark mode
- Add scientific calculator functions
- Improve UI animations
