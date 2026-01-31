Problem Statement
In medical emergencies, patients and their families often face serious difficulties in finding the required blood group, organ donors, or nearby hospitals on time. Information is usually scattered across different sources, unverified, and not available in real time. Due to the lack of a centralized and trusted system, precious time is lost in calling hospitals, searching donors, or relying on social media, which can result in delayed treatment and even loss of life. Additionally, there is no proper mechanism to verify donors or track their availability and medical eligibility. This gap between donors, patients, hospitals, and doctors highlights the need for a reliable digital platform that can quickly connect all stakeholders during emergencies and reduce response time.

        User (Patient / Donor)
               |
               v
        Web Browser (UI)
               |
               v
      React Frontend Application
   (Forms, Emergency Button, Map)
               |
               v
     Backend / API Layer (Future)
   (Auth, Requests, Verification)
               |
               v
        Database (Future)
   (Users, Donors, Requests)
               |
               v
   Hospital / Doctor Verification
        (Approval System)
        Frontend
React.js – Used to build the user interface and manage components like donor forms, emergency requests, popups, and verification status.

JavaScript – Handles application logic, user interactions, and dynamic behavior.

HTML – Provides the basic structure of the web application.

CSS – Used for styling, layout, animations, buttons, backgrounds, and overall UI design.

Development Tools
Node.js & npm – Used for project setup, dependency management, and running the development server.

VS Code – Code editor used for development.

Git & GitHub – Used for version control and project repository management.


AI tools Used
EMERGENT AI FOR WEBSITE 
GENSPARK AI FOR PRESENTATION
CHAT GPT FOR PROMPTS

PROMTS STRATEGY SUMMARY
While building Sanjeevani Connect, we used AI in a very natural and step‑by‑step way. Instead of asking for everything at once, we gave small and clear prompts for each part of the project. We started by explaining the idea and problem, then slowly asked for help in creating the UI, adding donor registration, emergency features, hospital maps, and verification status.

Whenever we faced errors or wanted improvements, we described the issue in simple language and updated the code accordingly. We also used prompts to improve the design, make the app more interactive, and organize the project properly. Later, AI was used to help write documentation like the problem statement, architecture diagram, tech stack explanation, and pitch presentation.

This approach made development faster and more organized. By continuously refining our prompts and giving feedback, we were able to build a clear, functional, and presentable project. Overall, the prompt strategy helped us turn our ideas into a working solution efficiently and with better clarity.

Step 1: System Requirements
Make sure the system has:

A computer (Windows / macOS / Linux)

Internet connection

Node.js installed (version 16 or above recommended)
Step 2: Clone the Repository
Clone the project from GitHub using the command:
git clone <your-github-repo-link>

Step 3: Install Dependencies
Install all required packages using npm:

npm install
This will automatically install React and other dependencies listed in package.json.

Step 4: Add Required Files
Make sure the following files exist:

src/App.js

src/App.css

public/logo.jpeg (project logo)

No extra configuration is required.

Step 5: Run the Application
Start the development server:

npm start
The application will run on:

http://localhost:3000
Step 6: Verify the Output
Once the app loads in the browser, you should be able to:

View the home page

Use Register as Donor

Request Blood or Organ

Use the Emergency button

View nearby hospitals on the map

See verification status and popups

Step 7: Reproduce on Any System
These steps can be repeated on any machine with Node.js and internet access, ensuring the project is fully reproducible without any additional setup.




