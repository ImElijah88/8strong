8 Strong Quiz
A web-based quiz application for testing knowledge of Java fundamentals, built with HTML, CSS, and JavaScript. The application features a dynamic and interactive UI with a glassmorphism design and a global high score leaderboard powered by Firebase.

Features
Interactive Quiz: Test your Java knowledge with 21 multiple-choice questions on various topics.

Dynamic UI: Bouncing, interactive spheres serve as answer choices.

Scoring System: Earn points for correct answers and track your progress in real time.

Attempt Limiter: Each question has a 5-attempt limit, adding a strategic element to the game.

Global Leaderboard: Users can register and log in to save their high scores to a global leaderboard powered by Firebase Firestore.

Responsive Design: The quiz is fully responsive and looks great on both mobile and desktop devices.

Secure Authentication: User registration and login are handled securely using Firebase Authentication.

Technologies Used
HTML5: The structure of the web page.

Tailwind CSS: For all styling, including the glassmorphism effects and responsive layout.

JavaScript (ES6+): The core logic for the quiz, including question handling, scoring, and UI manipulation.

Firebase:

Authentication: Manages user registration and login.

Firestore: A NoSQL cloud database for storing and retrieving high scores in real time.

Setup Instructions
To get this project running locally or deploy it, you will need to set up a Firebase project.

Clone the repository:

git clone [your-repository-url]
cd 8-strong-quiz

Create a Firebase Project:

Go to the Firebase Console.

Create a new project.

Add a web app to your project to get your Firebase configuration keys.

Enable Authentication and Firestore:

In your Firebase project, go to Authentication and enable the Email/Password sign-in method.

Go to Firestore Database and create a new database.

Update the Firebase Config:

Open the index.html file.

In the <script> tag, find the placeholder firebaseConfig variable.

Replace the placeholder values with the configuration from your Firebase project.

Run the application:

You can open the index.html file directly in your browser.

For more advanced development, you can use a local web server (e.g., Live Server in VS Code).

License
This project is open-source.
