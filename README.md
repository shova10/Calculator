🧮 Simple Web Calculator

This is a basic calculator built with HTML, CSS, and a touch of JavaScript. It allows users to perform simple arithmetic operations like addition, subtraction, multiplication, and division. It’s lightweight, visually clean, and perfect for practicing core front-end skills.
✨ Features

    Clean, responsive UI

    Supports:

        Addition (+)

        Subtraction (−)

        Multiplication (×)

        Division (÷)

    Special functions:

        AC to clear input

        DE to delete last character

        . for decimal point

        = to evaluate the expression

📁 Project Structure

📦 calculator/
├── index.html      # Main HTML file
├── style.css       # Styling for the calculator

🚀 How to Run It

    Download or clone this repository:

    git clone https://github.com/yourusername/calculator.git

    Open index.html in your browser.

        No build tools or installation needed – just open and go!

🧠 How It Works

    HTML defines the structure with buttons and a display.

    CSS styles it to look modern and centered.

    Inline JavaScript (within onclick) handles logic like:

        Adding characters to the display

        Evaluating the final expression with eval()

    ⚠️ Note: This calculator uses eval() for simplicity. It's okay for basic demos, but not recommended for production due to security risks.

🎨 Screenshot
![Calculator](https://github.com/user-attachments/assets/8c7e6671-5525-4fee-ab20-3356f79881ad)


📌 To-Do (Optional Improvements)

    Add keyboard support

    Validate input to prevent invalid expressions

    Improve UI responsiveness for mobile devices

    Replace eval() with a custom expression parser
