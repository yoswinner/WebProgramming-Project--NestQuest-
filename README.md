# 🏠 NestQuest - Smart Roommate Compatibility Finder

## 📌 Project Overview
NestQuest is a web application designed to solve a real-world problem for students: finding the perfect roommate. Instead of random hostel pairings, NestQuest uses a custom compatibility algorithm based on lifestyle preferences (sleep schedule, cleanliness, study habits, and social energy) to suggest ideal matches.

This project was developed as part of the **BCSE203E Web Programming Digital Assignment IV**.

## ✨ Key Features & Technical Implementations
* **Authentication UI (`login.html`):** Custom login/signup interface with strict password validation (minimum 8 characters, uppercase, number, and special symbol) and a dynamic password strength meter.
* **Interactive Profile Creation (`index.html`):** A two-step form process capturing personal details and roommate preferences, utilizing HTML5 validation (e.g., Age constrained to 16-50, required fields).
* **Tinder-Style Swipe Mechanics (`match.html`):** Draggable profile cards allowing users to visually accept or pass on potential roommates.
* **Custom Matching Algorithm:** Dynamically calculates a percentage score based on user lifestyle preferences and explains *why* users matched.
* **Dynamic Dashboard (`dashboard.html`):** A tabbed interface (All, Connected, Passed, Suggested) with real-time text searching and multi-parameter sorting.
* **Integrated Email Composer:** A custom modal form (`mailForm`) that grabs the matched user's data and connects directly to the native mail client.
* **Modern UI/UX (`style.css`):** Fully responsive Glassmorphism design with a seamless Light/Dark mode toggle (🔮).

## 🛠️ Technologies Used
* **HTML5:** Semantic structure and built-in form validation.
* **CSS3:** Custom variables, CSS Grid, Flexbox, Glassmorphism backdrop-filters, and keyframe animations.
* **Vanilla JavaScript:** DOM Manipulation, event routing, algorithm calculations, and `LocalStorage` for database state management.

## 🚀 Setup & Execution Instructions
Since this is a front-end application utilizing Vanilla JavaScript and LocalStorage, no complex backend or server setup is required.

1. Clone this repository to your local machine.
2. Open the project folder.
3. Double-click on `login.html` to launch the application in any modern web browser.
4. *Note: For the absolute best experience (and to avoid strict local CORS policies on some browsers), we recommend opening the project using the "Live Server" extension in VS Code.*

## 👨‍💻 Development Team
* **Anjini Pandey** (24BCE0714) 
* **Yash Pradhan** (24BCE0702) 
* *School of Computer Science & Engineering, VIT Vellore*
