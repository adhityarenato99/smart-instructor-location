# Instructor Locator Map

An interactive web application for visualizing instructor locations. This tool allows users to quickly find instructors by name or skill using a dynamic search feature built on an interactive Leaflet.js map.

![Uploading image.png…]()


---

## ✨ Features

- **Interactive Map:** Displays instructor locations using markers on a map powered by Leaflet.js.
- **Global Search:** A powerful search bar allows you to find any instructor across all cities by their **name** or **skill** (e.g., "Python", "Aruna Pandu").
- **Dynamic Results:** Search results appear instantly as you type.
- **Click to Locate:** Clicking a search result automatically pans the map to the instructor's city and opens a popup with details.
- **Detailed Popups:** Each city marker provides a list of local instructors, their skills, and the total count for that city.
- **In-Popup Filtering:** Each popup has its own filter to narrow down the list of instructors in a specific city.
- **Self-Contained:** The entire application runs from a single `index.html` file with no server-side dependencies.

---

## 💻 Technology Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **[Leaflet.js](https://leafletjs.com/)**: An open-source JavaScript library for mobile-friendly interactive maps.

---

## 🛠️ How to Use

No installation is needed! Simply download the `index.html` file and open it in your web browser.

---

## 📊 Data Structure

Instructor data is stored directly in the `index.html` file within a JavaScript array named `citiesData`. To add or modify data, edit this array. Each city object follows this structure:

```javascript
{
    lat: -6.9175,
    lon: 107.6191,
    city: 'Bandung',
    count: 2,
    instructors: [
        { name: 'Rahmat Pradana', skill: 'English for Business' },
        { name: 'Arfian Mauliddan', skill: 'Figma' }
    ]
}


