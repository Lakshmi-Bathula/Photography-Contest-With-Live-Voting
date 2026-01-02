
**📸 Photography Contest with Live Voting**


**📌Overview**

This project is a full-stack web application that allows users to participate in photography contests and vote in real time. It includes an admin dashboard for contest management, a user interface for submissions, and a live voting system powered by WebSockets. The application is designed to provide a seamless, interactive contest experience.

**🚀 Features**

Admin dashboard to create, manage, and delete contests

Contest scheduling with start and end time management (IST)

Photo submission by users

Live voting with real-time updates using WebSockets

View contest status: Upcoming, Active, and Ended

Admin view to review submissions of ended contests

Responsive and user-friendly UI


**🛠 Tech Stack**

**Frontend**

React.js

CSS

React Router

**Backend**

Node.js

Express.js

Socket.IO (for live voting updates)

**Database**

MySQL (contest data, users, submissions, votes)

Other Tools

Moment.js – Date & time handling (IST timezone)

REST APIs – Backend communication

**🔄 Application Workflow**

Admin logs in and creates a photography contest with title, theme, time window, and guidelines.

Users log in and submit photos during the active contest period.

Voting happens live, with real-time updates reflected instantly.

Contest status automatically changes based on time.

Admin can view submissions for ended contests and manage data.

**📊 Admin Dashboard**

Create and manage contests

View active and ended contests

Access all user submissions

Real-time contest status updates

**🖼 User Module**

View active contests

Submit photos to contests

Participate in live voting

View contest results

**▶️ How to Run the Project**

Clone the repository.

Install frontend dependencies:

npm install


Install backend dependencies:

npm install


Set up the MySQL database and update credentials.

Start the backend server:

npm start


Start the frontend application:

npm start


Open the application in your browser.

**📈 Learning Outcomes**

Built a complete full-stack application

Implemented real-time features using WebSockets

Gained experience with React routing and state management

Designed an admin dashboard and user workflows

Worked with date-time logic and contest automation
