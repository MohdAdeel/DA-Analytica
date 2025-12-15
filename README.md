# Data Finance 💹

Data Finance is a modern **React 18** web application built using **Create React App**, styled with **Tailwind CSS**, and enhanced with smooth typing animations using **react-type-animation** (React 18 compatible).

This project is lightweight, responsive, and ideal for finance-themed landing pages or dashboards.

---

## 🚀 Features

* Built with **React 18**
* Fully responsive UI using **Tailwind CSS**
* Smooth typing animation using **react-type-animation**
* Icons via **react-icons**
* Testing setup with **Jest + React Testing Library**
* Fast and optimized builds using **react-scripts**
* Clean and scalable code structure

---

## 📦 Tech Stack

* React 18
* Tailwind CSS
* react-type-animation
* react-icons
* React Scripts (CRA)
* Jest + React Testing Library

---

## 📁 Folder Structure

```txt
data-finance-yt/
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
│   └── index.css
│
│── package.json
│── tailwind.config.js
│── postcss.config.js
│── README.md
│── .gitignore
```

---

## 📥 Clone the Repository

```bash
git clone <repository-url>
cd data-finance-yt
```

---

## 📦 Install Dependencies

```bash
npm install
```

### If installation errors appear:

#### Windows

```bash
rmdir /s /q node_modules
del package-lock.json
npm install
```

#### Linux / macOS

```bash
rm -rf node_modules
rm package-lock.json
npm install
```

---

## ▶️ Start Development Server

```bash
npm start
```

Your app will be available at:

👉 [http://localhost:3000](http://localhost:3000)

---

## 📦 Build for Production

```bash
npm run build
```

---

## 🧪 Run Tests

```bash
npm test
```

---

## 🔧 Available Scripts

| Command       | Description             |
| ------------- | ----------------------- |
| npm start     | Run development server  |
| npm run build | Build for production    |
| npm test      | Run tests               |
| npm run eject | Eject CRA configuration |

---

## 🎨 Tailwind CSS Configuration

Ensure **index.css** includes:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

And **tailwind.config.js** contains:

```js
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

---

## ⌨️ Typing Animation (React 18 Compatible)

This project uses **react-type-animation** instead of `react-typed`.

### Installation

```bash
npm install react-type-animation
```

### Example Usage

```js
import { TypeAnimation } from 'react-type-animation';

<TypeAnimation
  sequence={['Finance Solutions', 2000, 'Data Analytics', 2000, 'Smart Investments', 2000]}
  wrapper="span"
  speed={50}
  repeat={Infinity}
/>
```

---

## ⚠️ Important Notes

* This project uses **Create React App**, which is now **deprecated** by the React team.
* For new projects, **Vite** or **Next.js** is recommended.
* Tailwind CSS must be properly configured for styles to work.
* Typing animation is React 18 safe using `react-type-animation`.

---

## 📜 License
This project is open-source and free to use for learning and development purposes.

This project is open-source and free to use for learning and development purposes.
