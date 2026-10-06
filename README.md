# Student Profile – React

A simple and reusable **Student Profile application built using React.js and Props**.
This project demonstrates how data can be passed from a parent component to a reusable child component using React Props.

## 🚀 Live Demo

**[View Live Project](https://muthukoornandini.github.io/student-profile-react/)**

## 📂 GitHub Repository

**[View Source Code](https://github.com/muthukoornandini/student-profile-react)**

## 🎯 Objective

To create a reusable `Student` component and display student details by passing information through **Props**.

## 🛠️ Technologies Used

* React.js
* JavaScript (JSX)
* Vite
* HTML
* CSS
* Git & GitHub
* GitHub Pages

## ✨ Features

* Reusable React `Student` component
* Student information passed using Props
* Displays student name, roll number, course, and college
* Simple and clean card-based layout
* Responsive presentation
* Deployed using GitHub Pages

## 📋 Student Details

The application displays:

* **Name:** Rahul
* **Roll No:** 101
* **Course:** BCA
* **College:** ABC College

## 🔄 How It Works

The `App` component passes student information to the `Student` component using Props.

```jsx
<Student
  name="Rahul"
  rollNo="101"
  course="BCA"
  college="ABC College"
/>
```

The `Student` component receives these Props and displays them:

```jsx
function Student(props) {
  return (
    <div>
      <h2>Student Profile</h2>
      <p>Name : {props.name}</p>
      <p>Roll No : {props.rollNo}</p>
      <p>Course : {props.course}</p>
      <p>College : {props.college}</p>
    </div>
  );
}
```

## 📁 Project Structure

```text
student-profile/
│
├── public/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── App.css
│   ├── Student.jsx
│   ├── index.css
│   └── main.jsx
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## ▶️ Run Locally

Clone the repository:

```bash
git clone https://github.com/muthukoornandini/student-profile-react.git
```

Navigate to the project:

```bash
cd student-profile-react
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The application will then run on the local Vite development server.

## 📚 Concepts Demonstrated

* React Components
* JSX
* Props
* Component Reusability
* Vite
* Git & GitHub
* GitHub Pages Deployment

## 🌐 Deployment

The project is deployed using **GitHub Pages**.

**Live Demo:**
https://muthukoornandini.github.io/student-profile-react/

## 👩‍💻 Author

**Muthukoornandini**

B.Tech – Artificial Intelligence & Data Science

---

⭐ If you find this project useful, feel free to explore the repository.
