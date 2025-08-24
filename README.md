##📚 Book Bridge
Book Bridge is a web-based platform designed to facilitate the seamless donation and receipt of books. It connects generous donors who wish to give their pre-loved books a new life with recipients who are looking for their next great read. This project aims to promote literacy, reduce waste, and foster a community of sharing, all through an intuitive and user-friendly interface.

✨ Features
Dual User Interface: Separate, streamlined forms for Donors and Recipients to specify their intents clearly.
Book Categorization: Donors can categorize their books (e.g., Educational, Fiction, Programming, History) for better matching and discovery.
Location Awareness: Integrated geolocation API to help coordinate pick-ups and deliveries based on user proximity.
Centralized Dashboard: A clean sidebar navigation dashboard provides quick access to all parts of the application.
Responsive Design: The application is styled to be visually appealing and functional across various device screen sizes.
Team Transparency: A dedicated contact page lists all project contributors, making collaboration transparent.

🛠️ Tech Stack
HTML5: Used for creating the structure and content of all the web pages (e.g., forms, headings, lists).
CSS3: Used for styling the website. 
This includes:
*Layout: Flexbox and margin: auto for centering elements.
*Styling: Colors, fonts, padding, borders, and shadows.
*Backgrounds: Using the background-image property to set background pictures.
*Responsive Design: The @media rule (though not heavily used) and relative units for some sizing.
JavaScript (Vanilla JS): Used to add interactivity to the pages. 
Specifically:The getCurrentPosition() method from the Geolocation API to get the user's location.Basic DOM manipulation (e.g., getElementById, innerHTML).Functions like submitDonation() and Confirm() to handle form button clicks and show alerts.


📁 Project Structure
text
book-bridge/
│
├── index.html          # Main dashboard with navigation
├── donorpage.html      # Form for users to donate books
├── recipient.html      # Form for users to request books
├── Location Page.html  # Page to fetch and display user's geolocation
├── contactpage.html    # Page displaying team contact information
│
├── style.css          # (Referenced but not provided) Main stylesheet
├── sidebar.css        # (Referenced but not provided) Styles for the dashboard sidebar
│
├── cm1.jpg            # Background image for contact page
├── books1.jpg         # Background image for donor/recipient pages
├── wm3.jpg            # Background image for location page
├── 493411.png         # Donate button icon
└── heart.png          # Receive button icon
🚀 How to Use
Dashboard: Start at the index.html dashboard.

Donate a Book:
Click on the "Donor" link in the sidebar or the "DONATE" button.
Fill out the form with your details, book information (name, author, type), and your location.
Submit the form to "Make Donation".

Receive a Book:
Click on the "Recipient" link in the sidebar or the "RECIEVE" button.
Enter your name, email, and the book you are interested in.
Click "Confirm" to finalize your request.

Location Services: Use the "Location" page to share your geographic coordinates, which can help in organizing logistics.

Contact: The "Contact" page provides the information of all team members behind the project.
