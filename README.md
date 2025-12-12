Data Finance

Data Finance is a modern React 18 web application built using Create React App, styled with Tailwind CSS, and enhanced with smooth typing animations using react-typed.
This project is lightweight, responsive, and suitable for finance-themed landing pages or dashboards.

🚀 Features

Built with React 18

Fully responsive UI using Tailwind CSS

Smooth typing animation using react-typed

Icons via react-icons

Testing setup with React Testing Library

Fast and optimized builds using react-scripts

Clean and scalable code structure



📦 Tech Stack

React 18

Tailwind CSS

React Typed

React Icons

React Scripts (CRA)

Jest + React Testing Library



📁 Folder Structure

data-finance-yt/
│── node_modules/
│── public/
│   ├── index.html
│   └── favicon.ico
│
│── src/
│   ├── components/
│   ├── assets/
│   ├── pages/
│   ├── App.js
│   ├── index.js
│   └── styles/ (if used)
│
│── package.json
│── tailwind.config.js
│── postcss.config.js
│── README.md
│── .gitignore


Clone the Repository
git clone <repository-url>
cd data-finance-yt


-- Install Dependencies

npm install

If installation errors appear:

Windows:

rmdir /s /q node_modules
del package-lock.json
npm install



Linux

rm -rf node_modules
rm package-lock.json
npm install



▶️ Start Development Server

npm start


Your app will be available at:
http://localhost:3000


📦 Build for Production
npm run build


-- Run Test

npm test


🔧 Available Scripts
Command	Description
npm start	     Run development server
npm run build	    Build for production
npm test	        Run tests
npm run eject	      Eject CRA configuration


To ensure Tailwind works properly, confirm that index.css includes:

@tailwind base;
@tailwind components;
@tailwind utilities;



❗ Important Notes

This project uses React 18.

Make sure Tailwind CSS is properly configured for styling.

Typing effects require importing react-typed correctly.

Example

import Typed from "react-typed";





