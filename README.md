# SkillShare-PeerLearning-Platform
📚 SkillShare – Peer Learning & Mentorship Platform

A full-stack Java web application that connects students based on the skills they want to teach and learn, enabling automated mentor–mentee matching with a clean, modern dashboard UI.

🚀 Features
🔐 User Authentication – login, logout, session management
👤 User Profile – view & edit name, teach skill, learn skill
🔄 Mentor–Mentee Matching using HashMap + graph-based logic
📊 Interactive Dashboard – user stats, skills analytics (Chart.js)
🧭 Responsive UI with TailwindCSS
🔎 View All Users (protected route – only logged-in users)
🧵 UTF-8 Support for Indian languages
🔒 Secure Servlets – protected pages for authenticated users only

🛠️ Tech Stack
Frontend :
HTML5
JSP
TailwindCSS
JavaScript
Chart.js
Backend :
Java (Core Java, OOP)
Servlets (Jakarta Servlet API)
JSP (Server-side rendering)
MVC-based structure
Database
MySQL
JDBC (PreparedStatements, CRUD)
Server
Apache Tomcat 10.1

Tools
Eclipse IDE
MySQL Workbench
Git & GitHub

🧰 Project Structure
SkillShare-PeerLearning-Platform/
│
├── src/main/java/com/peerlearning/
│   ├── dao/        → Database operations (UserDAO)
│   ├── model/      → User model (POJO)
│   └── servlet/    → Login, Logout, Users, Matches, UpdateProfile Servlets
│
├── src/main/webapp/
│   ├── WEB-INF/
│   │   └── web.xml (Servlet mappings)
│   ├── EditProfile.jsp
│   ├── UserDashboard.jsp
│   ├── login.jsp
│   ├── matches.jsp
│   └── register.html
│
└── README.md

🔄 How Matching Works

The matching system uses:
HashMap → map teach skills & learn skills
Graph concept → connect users through teach/learn edges
For each user:
Find mentors = users who teach what current user wants to learn
Find mentees = users who want to learn what current user can teach
This makes the platform dynamic and personalized.

📸 Screenshots



🎯 Future Enhancements
Skill search + filters
Admin panel
Notifications
Real-time chat
Follow/Connect system

🙌 Author

Pranav Gaikwad
SkillShare – Peer Learning Platform
Built with Java, Servlets, JSP, JDBC, MySQL, TailwindCSS
