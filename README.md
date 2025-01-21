# RB Scouting Grader

## Overview
The **RB Scouting Grader** is a simple and user-friendly tool designed to help evaluate and grade running backs based on specific attributes. It calculates a final scouting score based on user input for attributes like speed, agility, vision, and more.

This project provides a web-based interface where users can input grades and view the final score directly in their browser.

---

## Folder Structure
```plaintext
RB_Scouting_Grader/
├── index.html        # The main HTML file for the web app
├── script.js         # JavaScript logic for grading (optional if embedded in HTML)
├── styles.css        # CSS for styling the app (optional)
├── README.md         # This README file
```

---

## Getting Started

### Prerequisites
To use this tool, all you need is a modern web browser (e.g., Chrome, Firefox, Safari).

### Installation
1. Download or clone the repository:
   ```bash
   git clone https://github.com/yourusername/RB_Scouting_Grader.git
   ```
2. Navigate to the project folder:
   ```bash
   cd RB_Scouting_Grader
   ```
3. Open the `index.html` file in your browser.

### Usage
1. Open `index.html` in a browser.
2. Enter grades for each attribute in the provided input fields.
3. Click the **Calculate Final Grade** button to view the final score.
4. Adjust inputs as needed to see how the final grade changes.

---

## Features
- **User-Friendly Interface**: Intuitive design for easy input and real-time calculations.
- **Detailed Breakdown**: Grades divided into categories like Physical Attributes, Vision, and more.
- **Final Score Calculation**: Automatically computes the final grade based on weighted attributes.

---

## Customization
To modify the attributes or weights:
1. Open the `script.js` file (or edit the `<script>` tag in `index.html` if embedded).
2. Adjust the categories, attributes, and weights to match your needs.

Example:
```javascript
const categories = {
    "Physical Attributes": {
        attributes: ["Speed", "Agility", "Power", "Balance"],
        weight: 15
    },
    // Add or modify categories here
};
```

---

## Contributing
Feel free to submit issues or pull requests to improve the tool. Contributions are always welcome!

---

## License
This project is licensed under the MIT License.

