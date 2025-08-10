# Task4-08-08-2025
📌 Objective
Convert an existing desktop-only page into a mobile-friendly layout using CSS media queries.

🛠 Tools Used
HTML & CSS

VS Code

Chrome DevTools (Device Toolbar)

🚀 Steps to Run
Open the project in VS Code.

Open the HTML file in your browser.

Resize the browser window or use Chrome DevTools → Toggle Device Toolbar → Select a mobile device.

The page should adjust layout, font size, and navigation for smaller screens.

🗂 Features Implemented
Media Query for screens with max-width: 768px

Responsive nav menu (stacks vertically on small screens)

Images resize to fit container (max-width: 100%)

Text and layout adjust for better mobile readability

📜 Example CSS Media Query
css
Copy
Edit
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
  nav ul {
    flex-direction: column;
    align-items: center;
  }
  img {
    max-width: 100%;
    height: auto;
  }
}
