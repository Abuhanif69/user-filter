Live User Filter

A simple live user search and filter app built with HTML, CSS, and vanilla JavaScript.
Users can search by name or location, and results update instantly as they type.
🔗 Live Demo: https://abuhanif69.github.io/user-filter/

📌 Overview

The Live User Filter fetches random user data from an external API and displays it in a scrollable list.
As the user types into the search input, the list is filtered in real time based on name or location.
This project focuses on:
.Working with APIs
.Asynchronous JavaScript (async/await)
.DOM manipulation
.Live filtering logic

✨ Features
🔍 Live search filtering (no refresh required)
🌍 Search by name or location
🧑 Displays user avatar, full name, and city/country
⚡ Fetches real data from the Random User API
🎨 Clean and minimal UI

🛠️ Built With
.HTML5
.CSS3
.JavaScript (ES6)
.Random User API – https://randomuser.me

📂 Project Structure
user-filter/
│
├── index.html
├── style/
│   └── style.css
└── script/
    └── main.js

⚙️ How It Works

Fetch Users

On page load, the app fetches 150 users from the Random User API.

Render Users

Each user is displayed with an image, name, and location.

Store List Items

User list elements are stored in an array for easy filtering.

Live Filtering

As the user types, JavaScript checks if the search term matches the text content.

Non-matching users are hidden using a CSS class.

📚 What I Learned

How to fetch and handle API data using fetch and async/await

How to dynamically create and update DOM elements

Implementing real-time filtering logic

Managing UI updates efficiently with JavaScript

📄 License

This project is open-source and available under the MIT License.
