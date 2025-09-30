# 💀 Danger Ahead

This is a simple, spooky, horror-themed landing page created with HTML and CSS. It features a custom font and a scary background to give it a unique and spooky look.

## 🚀 Live Demo

<a href="https://jitesh-saini.github.io/HTML-CSS-2/">Live Project Link</a>

## 📸 Screenshot

<img width="1917" height="926" alt="Screenshot 2025-09-30 023955" src="https://github.com/user-attachments/assets/862d651d-7fa9-48dd-90b5-861dbc7b2eed" />


## 🛠️ Tech Stack

-   HTML5
-   CSS3
-   Custom Font (Another Danger)

## ✨ Features

-   Spooky, horror-themed design.
-   Uses the custom "Another Danger" font for a unique look.
-   A styled button with a warning message.


## ⚙️ Installation

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Jitesh-Saini/HTML-CSS-2.git](https://github.com/Jitesh-Saini/HTML-CSS-2.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd HTML-CSS-2
    ```
3.  **Open the `index.html` file:**
    Simply open the `index.html` file in your web browser, and the project will be live!


## 📂 File Structure

/
|-- images/
|   |-- horror.jpg
|-- fonts/
|   |-- Another Danger - Demo.otf
|-- index.html
|-- style.css
|-- README.md


## 👨‍💻 Author

-   ** JITESH SAINI **
-   GitHub: [@Jitesh-Saini](https://github.com/Jitesh-Saini)
-   
## 🙏 Credits

-   **Font:** "Another Danger - Demo" by The Branded Quotes.

## ✨ CSS

@font-face {
    font-family: f1;
    /* Path updated for the 'fonts' folder */
    src: url(./fonts/Another\ Danger\ -\ Demo.otf);
}

*{
    margin : 0;
    padding: 0;
    box-sizing: border-box;
}
html, body {
    height: 100%;
    width: 100%;
}

#main{
    height: 100%;
    width: 100%;
    background-image: url(./images/horror.png);
    background-size: cover;
    background-position: upper;
    text-align: center;
}
#main h1{
    color: black;
    text-align: center;
    padding-top: 20px;
    font-size: 100px;
    font-family: f1;
    font-weight: 100;

}

#main button{
    display: block;
    margin: 400px auto 0 625px;
    padding: 15px 30px;
    font-size: 20px;
    background-color: rgba(0, 0, 0, 0.749);
    color: red;
    border: 2px solid red;
    border-radius: 10px;
    cursor: pointer;
    box-shadow: 2px 2px 4px #000000;
}
