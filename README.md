Poetic Quote Generator
This is a simple web application that generates a poetic quote and a corresponding background image based on user-defined inputs. The application is a single-page HTML file with accompanying CSS and JavaScript files.

Features
Quote Generation: Fetches a poetic and witty quote from an API based on a user's favorite activity and place.

Image Generation: Fetches a random background image from the Unsplash API based on the user's favorite place.

User Customization: Allows the user to easily change their name, favorite activity, favorite place, and the AI's "creativity temperature."

Loading State: Displays a loading spinner and message while fetching data from the APIs.

How to Use
Open index.html in your web browser.

Open index.js in a text editor.

Modify the variables at the top of index.js to customize the output:

name: Your name, which will be displayed as the quote's author.

favoriteActivity: Your favorite activity (e.g., "Cooking", "Reading", "Hiking").

favoritePlace: Your favorite place (e.g., "Cafe", "Forest", "Paris").

temperature: A number between 0 and 1 to control the AI's output. A higher number results in more random and creative quotes.

Optionally, replace the avatar.jpg file with a photo of yourself. Make sure the new file is also named avatar.jpg.

File Structure
index.html: The main HTML file that provides the structure for the web page.

index.css: Contains the styles for the application, including fonts, layout, and visual effects.

index.js: The main JavaScript file that imports the utils.js and calls the core function to generate content.

utils.js: Contains the logic for fetching data from the APIs and updating the page content.

avatar.jpg: The profile picture displayed on the page.

loading.gif: The animated GIF used for the loading spinner.

API Endpoints Used
Unsplash API: Used to fetch random images based on a query.

OpenAI API: Used to generate the poetic quotes.

Note: This project uses APIs that may require an API key or have usage limits. The current code is set up for a specific environment and may need adjustments if run locally.
