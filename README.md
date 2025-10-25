# PrimalTraining Website

##  Team Members
- **Yahia Sonbol** — ID: 22-101080  
- **Youssef Hazem** — ID: 22-101087  
- **Youssef Faltas** — ID: 22-101089  

---

##  Website Theme and Purpose
**PrimalTraining** is a modern fitness-themed website that connects users with top-tier trainers and personalized workout programs.  
It’s designed to inspire a commitment to fitness through professional coaching, community engagement, and clean modern visuals.  

**Purpose:**  
To help users find certified trainers, track progress, and stay motivated in an encouraging environment that promotes physical and mental growth.

---

##  Key Features
- **Dark Mode Toggle** — Switch between light and dark themes dynamically.  
- **Smooth Scrolling Navigation** — Built-in anchor navigation for better UX.  
- **Animated Headings** — Dynamic scrolling captions for engagement.  
- **Accessible Contact Section** — Email and phone links for easy connection.  

---

## Key JavaScript Functions
```js
const darkModeToggle = document.getElementById('darkModeToggle');
const body = document.body;

darkModeToggle.addEventListener('click', () => {
    body.classList.toggle('dark-mode');
});
