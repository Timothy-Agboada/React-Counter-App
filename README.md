## 🚀 30-Day Coding Challenge: Day 13

This project marks the thirteenth entry in my 30-day coding challenge and my first step into the world of **React**. The goal was to build a classic counter application to understand the fundamental concepts of the React library, including components, state, and JSX.

### 📖 Project Overview

This is a simple but fully functional counter application built with React. It allows users to increment, decrement, and reset a number. The entire application is built within a single HTML file using CDN links for React, ReactDOM, and Babel, making it a perfect introduction to the core principles of React without the complexity of a full development environment.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-21-2025 21-21-43](https://github.com/user-attachments/assets/332ce246-d63c-413f-b9a6-17ef0a326a8e)


### 🌟 Key Features

* **Component-Based:** The entire UI is encapsulated within a single, functional React component.
* **State Management:** Uses the `useState` hook to manage the counter's value, demonstrating the core concept of state in React.
* **Event Handling:** Handles user clicks to trigger state updates for incrementing, decrementing, and resetting the count.
* **Declarative UI with JSX:** The user interface is written using JSX, showcasing how React mixes HTML-like syntax with JavaScript logic.
* **Instant UI Updates:** React automatically re-renders the component whenever the state changes, ensuring the display is always in sync with the data.
* **Modern Styling:** Styled with Tailwind CSS for a clean and modern look.

### 💻 Technologies Used

This project introduces modern front-end libraries while maintaining a simple setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** The library used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript that browsers can execute.
* **Tailwind CSS:** For all styling and layout.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-counter-app.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-counter-app
    ```
3.  **Open the `index.html` file in your web browser:**
    * You can simply double-click the `index.html` file. The CDN links will handle loading React and Babel automatically.

No complex build steps or installations are required.

### 🎯 Learning Objectives

This project served as a foundational introduction to several critical React concepts:

* **Understanding React Components:** Learning how to create a basic functional component.
* **The `useState` Hook:** Getting hands-on experience with the most fundamental React hook for managing component state.
* **JSX Syntax:** Writing UI elements using JSX and embedding JavaScript expressions within it.
* **React Event Handling:** Using `onClick` to bind functions to user interactions.
* **The React Rendering Process:** Observing how `ReactDOM.createRoot()` and `root.render()` work together to mount the application to the DOM.
* **Basic React Setup via CDN:** Understanding how React can be used even without a complex build environment like Webpack or Vite.
