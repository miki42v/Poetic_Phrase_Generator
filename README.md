# Poetic Quote Generator ✨

A simple web app that generates **poetic quotes** inspired by your favorite activity and place, paired with a beautiful background image. Built with vanilla **HTML, CSS, and JavaScript**, it fetches quotes using the OpenAI API and images from Unsplash.

---

## 🚀 Features

* **AI-Powered Quotes:** Generates a poetic phrase in the witty, satirical style of Oscar Wilde.
* **Dynamic Backgrounds:** Fetches a random, high-quality Unsplash image based on your chosen place.
* **Simple Personalization:** Easily customize with your name, favorite activity, and favorite place.
* **Clean UI:** A minimal and responsive design that looks great on any device.
* **Efficient:** Uses `localStorage` to cache the last generated quote and image, reducing redundant API calls.

---

## 📂 Project Structure

├── index.html         # Main HTML structure
├── index.css          # Styling and layout
├── index.js           # Configuration and main script entry point
├── utils.js           # Core logic for API calls & DOM manipulation
├── avatar.jpg         # Default avatar image (you can replace this)
└── README.md          # This documentation file


---

## 🛠️ How to Use

This project requires no installation or build steps. Simply follow these instructions:

1.  **Clone or Download**
    Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/poetic-quote-generator.git](https://github.com/your-username/poetic-quote-generator.git)
    ```
    *(Replace with your actual repository URL)*

2.  **Customize Your Details**
    Open the `index.js` file in a text editor and update the configuration variables at the top:
    ```javascript
    // Your Name
    let name = "Your Name Here"
    
    // Your favorite things
    let favoriteActivity = "Your Favorite Activity"
    let favoritePlace = "Your Favorite Place"

    // Controls AI creativity (0.0 to 1.0)
    let temperature = 0.7 
    ```

3.  **(Optional) Update Your Avatar**
    Replace the existing `avatar.jpg` file with a photo of yourself. Make sure the new file has the exact same name (`avatar.jpg`).

4.  **Open in Browser**
    Open the `index.html` file directly in your web browser to see the result!

---

## 🎨 Customization

* **Theme & Fonts:** All colors and fonts can be changed by editing the CSS variables at the top of the `index.css` file.
* **AI Prompt:** You can modify the style of the generated quote by editing the `quotePrompt` string inside the `getQuote()` function in `utils.js`.

---

## 📦 APIs Used

* **OpenAI API** (via Scrimba Proxy) – Used to generate the poetic quotes.
* **Unsplash API** (via Scrimba Proxy) – Used to fetch the background images.

---

## 💡 Credits

This project was inspired by and built as part of a Scrimba learning module.

Built with ❤️ using HTML, CSS & JavaScript.
