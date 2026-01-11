📘 React Homework 01 — Components

This project was created as part of the React module and focuses on building reusable React components, passing data via props, and organizing a project using modern React best practices.

The application is built with Vite, styled using CSS Modules, and deployed to Vercel.

⸻

🔗 Links
	•	🔴 Live Demo (Vercel):
👉 PASTE YOUR VERCEL LINK HERE
	•	📦 GitHub Repository:
👉 https://github.com/kutluhangil/goit-react-hw-01

⸻

🛠 Technologies Used
	•	React
	•	Vite
	•	JavaScript (ES6+)
	•	CSS Modules
	•	Prettier
	•	ESLint

⸻

📂 Project Structure

Each component is placed in its own folder inside the src/components directory.
Every component folder contains:
	•	a .jsx file (component logic)
	•	a .module.css file (component styles)

src/
├── components/
│   ├── App/
│   │   ├── App.jsx
│   │   └── App.module.css
│   ├── Profile/
│   │   ├── Profile.jsx
│   │   └── Profile.module.css
│   ├── FriendList/
│   │   ├── FriendList.jsx
│   │   └── FriendList.module.css
│   ├── FriendListItem/
│   │   ├── FriendListItem.jsx
│   │   └── FriendListItem.module.css
│   └── TransactionHistory/
│       ├── TransactionHistory.jsx
│       └── TransactionHistory.module.css
│
├── userData.json
├── friends.json
├── transactions.json
└── main.jsx


⸻

✅ Project Requirements Fulfilled
	•	✔ Project created using Vite
	•	✔ Components built using React
	•	✔ All components exported using default export
	•	✔ All components rendered inside the root <App /> component
	•	✔ Props passed correctly to all components
	•	✔ Static data moved to JSON files
	•	✔ Styling implemented with CSS Modules
	•	✔ Code formatted with Prettier
	•	✔ No errors or warnings in the browser console
	•	✔ Project deployed to Vercel

⸻

📌 Tasks Overview

🧩 Task 1 — Social Media Profile

A <Profile /> component that displays user information:

Props:
	•	name
	•	tag
	•	location
	•	image
	•	stats (followers, views, likes)

User data is stored in userData.json and passed to the component via props.

⸻

🧩 Task 2 — Friend List

A <FriendList /> component that renders a list of friends.

Each friend is displayed using a <FriendListItem /> component.

Props:
	•	avatar
	•	name
	•	isOnline

The online status is visually indicated using conditional styling.

Friend data is stored in friends.json.

⸻

🧩 Task 3 — Transaction History

A <TransactionHistory /> component that renders a table of financial transactions.

Props:
	•	items (array of transaction objects)

Each transaction includes:
	•	type
	•	amount
	•	currency

Transaction data is stored in transactions.json.

⸻

🚀 How to Run Locally

npm install
npm run dev


⸻

📦 Build for Production

npm run build


⸻

🌐 Deployment

The project is deployed using Vercel.
The production build is automatically generated and served after deployment.

⸻

👨‍💻 Author
Kutluhan Gil
