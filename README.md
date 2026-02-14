📝 Paste Management App

A simple paste management application built with React, Redux, React Router, and Tailwind CSS.
Users can create, view, and manage text snippets (pastes), similar to a lightweight Pastebin.

🚀 Features

Create, view, and delete pastes

Dynamic routes with React Router (/pastes/:id)

Global state management using Redux

Persistent storage with localStorage

Dark mode theme with Tailwind CSS (bg-black, text-white)

Responsive design for desktop and mobile

🛠 Tech Stack
Feature	Technology
Frontend	React (Functional Components)
State Management	Redux Toolkit
Routing	React Router v6
Styling	Tailwind CSS
Persistence	LocalStorage
Notifications	react-hot-toast
⚡ Installation

Clone the repository:

git clone https://github.com/your-username/paste-management-app.git
cd paste-management-app


Install dependencies:

npm install


Run the development server:

npm run dev


Open the app in your browser:

https://paste-saver-lilac.vercel.app/

🖥 Folder Structure
src/
├─ components/
│  ├─ Navbar.jsx
│  ├─ Home.jsx
│  ├─ Paste.jsx
│  └─ ViewPaste.jsx
├─ Redux/
│  ├─ store.js
│  └─ pasteSlice.js
├─ App.jsx
├─ main.jsx
└─ index.css

📦 Usage

Home Page: View all saved pastes

Create Paste: Add new pastes via the Paste form

View Paste: Click on a paste to see its content (/pastes/:id)

Delete Paste: Remove unwanted pastes

🔧 How It Works

Each paste is stored as an object:

{
  id: 'unique-id',
  title: 'Paste Title',
  content: 'Paste Content'
}


Redux stores the pastes and syncs with localStorage for persistence

React Router handles navigation without reloading the page

Tailwind CSS provides responsive styling and a clean dark theme

🌟 Challenges & Learnings

Managing state persistence between Redux and localStorage

Implementing dynamic routing for individual pastes

Building a responsive UI with Tailwind CSS

Learning how to structure a real-world React project

📈 Future Improvements

Add user authentication for private pastes

Integrate a backend database (e.g., Firebase or Node.js + MongoDB)

Implement search and filter functionality

Dark/light mode toggle
