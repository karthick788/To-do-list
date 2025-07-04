📝 Premium To-Do List (Glass UI Edition)
A beautiful, responsive to-do list web application with user authentication built using HTML, CSS (with Bootstrap & custom styles), and vanilla JavaScript. Tasks are saved locally using localStorage. The UI includes modern glassmorphism and supports task priorities.

🚀 Features
✅ User Authentication

Sign up with username, email, and password.

Login with stored credentials.

Client-side validation and session tracking via localStorage.

🗂️ Task Management

Add new tasks with:

Name

Optional description

Priority (High, Medium, Low)

Tasks are stored persistently in localStorage.

Toggle task completion.

Delete tasks with a click.

🎨 UI Design

Glassmorphism-inspired style.

Responsive layout using Bootstrap.

Priority-colored task cards.

Background image: back.jpg.

📁 Project Structure
bash
Copy code
📦 premium-todo/
├── index.html         # Main to-do list app (post-login)
├── login.html         # Login screen
├── signup.html        # Sign-up screen
├── back.jpg           # Background image
└── README.md          # Project description

Use login.html to access the app.

Once logged in, you'll be redirected to index.html.

💾 Data Persistence
All users and task data are stored in the browser's localStorage.

No server or database is required.

🔐 Note on Security
This app is for educational/demo purposes.

No encryption or hashing for passwords — do not use real credentials.

In production, authentication and storage must use secure backend systems.

📸 Screenshots
(Add screenshots of login, signup, and task pages here)

📌 Future Enhancements
Add drag-and-drop task reordering.

Integrate a real backend with authentication.

Enable deadline reminders or due dates.

Filter tasks by status or priority.

📃 License
This project is licensed under the MIT License.