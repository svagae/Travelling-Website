# Travelling-Website
Introduction
This project is a web application developed as part of the CSEN503 Introduction to Communication Networks course. The website allows users to explore travel destinations, maintain a personalized "Want-to-Go List," and search for destinations. The application is built using the client-server architecture and is hosted online using Render.

Features
User Registration:

Allows users to create an account.
Validates inputs to ensure unique usernames and non-empty fields.
User Login:

Enables users to log in with their credentials.
Redirects to the home page upon successful login or displays error messages for invalid attempts.
Home Page:

Displays travel destination categories (e.g., Beaches, Mountains).
Provides navigation to other features such as the "Want-to-Go List."
Destination Pages:

Show details about a destination.
Include an embedded video for each destination.
Offer an option to add destinations to the "Want-to-Go List."
Want-to-Go List:

Displays destinations saved by the user.
Prevents duplicate entries.
Search Functionality:

Allows users to search for destinations by name.
Displays clickable search results or a "Not Found" message.
Deployment:

The application is hosted on Render for online access.
Technologies Used
Backend: Node.js, Express.js
Frontend: Embedded JavaScript (EJS), HTML, CSS
Database: MongoDB
Session Management: express-session
Development Environment: Visual Studio Code

Usage Instructions
For Local Testing
Registration:
Register with a unique username and password.
Login:
Log in with registered credentials.
Explore:
Browse destination categories and pages.
Add destinations to the "Want-to-Go List."
Search:
Use the search bar to find destinations.
For Online Testing
Use the hardcoded credentials:
Username: admin
Password: admin.
File Structure
plaintext
Copy code
|-- public/
|   |-- css/               # Stylesheets
|   |-- js/                # Client-side scripts
|-- views/                 # EJS files for frontend views
|-- routes/                # Backend route handlers
|-- server.js              # Main server file
|-- package.json           # Project metadata and dependencies
