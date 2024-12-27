# 🔑Password Generator

## Description
This is a React-based password generator that creates secure, random passwords with customizable options such as length, inclusion of numbers, and special characters. It includes a responsive UI styled with Tailwind CSS.

## Features ✨

🔐 Generate random passwords.

🔢 Customize password length (6 to 100 characters).

✅ Option to include numbers.

🔤 Option to include special characters.

📋 Copy generated passwords to the clipboard with a single click.

## Link (https://password-generator-jade-mu.vercel.app/)
## Screenshot 📸

![Screenshot 2024-12-28 004717](https://github.com/user-attachments/assets/05e859d3-737b-44be-a5f1-d2f8ba349151)

 
 ## Technologies Used 💻

- React: For building the user interface.

- Tailwind CSS: For responsive and modern styling.

- JavaScript: For password generation logic.


  ##  🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abhishek526-star/Password-Generator.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Password-Generator
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Install Tailwind CSS:**
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init
   ```
5. **Configure Tailwind CSS in `tailwind.config.js`:**
   ```javascript
   module.exports = {
     content: ["./src/**/*.{js,jsx,ts,tsx}", "./public/index.html"],
     theme: { extend: {} },
     plugins: [],
   };
   ```
6. **Add Tailwind to your CSS file (e.g., `src/index.css`):**
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```
7. **Start the app:**
   ```bash
   npm run dev
   ```
