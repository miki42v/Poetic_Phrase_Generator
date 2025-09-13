✒️ Poetic Quote GeneratorThis project is a fun, personalized web application that generates a poetic quote and a background image using AI. You can customize it with your name, a favorite activity, and a favorite place to create a unique and visually appealing result.📊 FeaturesPersonalized Content: Generates a unique quote and background image based on your inputs.AI-Powered Creativity: Uses the OpenAI API to create poetic phrases in the witty style of Oscar Wilde.Dynamic Visuals: Fetches a random, high-quality background image from Unsplash that matches your favorite place.Simple Customization: Easily change the name, activity, and place directly in the index.js file.Adjustable AI: Control the creativity and randomness of the generated quote with a simple temperature setting.⚡ Technical StackFrontend: HTML5, CSS3, JavaScript (ES Modules)APIs:OpenAI API (for text generation)Unsplash API (for background images)Note: Both APIs are accessed via a Scrimba proxy.🚀 How to UseThis project runs directly in the browser without any installation steps.Download or Clone:Get a local copy of the project files.Customize Your Details:Open the index.js file and modify the following variables:// 1. Change the value of the variable to your name
let name = "Your Name Here"

// 2. Change the value of the variable to your favorite activity
let favoriteActivity = "Reading"

// 3. Assign the favoritePlace variable your favorite place
let favoritePlace = "a cozy library"

// 4. Configure the AI by setting a temperature from 0 to 1
let temperature = 0.7
(Optional) Change the Avatar:Replace the avatar.jpg file with your own photo. Make sure the new file is also named avatar.jpg.View Your Page:Open the index.html file in your web browser to see the result!🤖 How the AI WorksThis application uses AI to generate creative text. Here’s a quick breakdown:Prompt Engineering: The application takes your favoriteActivity and favoritePlace from the index.js file.API Call: It combines these into a carefully crafted prompt that is sent to the OpenAI API. The prompt specifically asks the AI to generate a phrase in the "insightful, witty and satirical style of Oscar Wilde."Creative Output: The API processes this request and returns a unique, poetic phrase that is then displayed on the screen.This project was inspired by a Scrimba course.
This project was inspired by a Scrimba course.
