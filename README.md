# 📘 Student Scoreboard (Assignment)

## 📝 Description

This project is a **Student Scoreboard Dashboard** built using **React** and **Tailwind CSS**.
It allows users to add students, update their scores, and view summary statistics such as total students, number of students passed, and average score.

---

## 🎯 Objective

The objective of this assignment is to:

* Understand **React functional components**
* Practice **state management using useState**
* Implement **dynamic rendering using map()**
* Perform **data calculations (filter, reduce)**
* Apply **Tailwind CSS for styling**

---

## ⚙️ Features

* Add new student with name and score
* Update student scores
* Display all student records in a table
* Show pass/fail status automatically
* Calculate:

  * Total number of students
  * Number of students passed (score ≥ 40)
  * Average score

---

## 🛠️ Technologies Used

* React JS
* JavaScript (ES6)
* Tailwind CSS

---

## 📂 Components

* **Heading.jsx** → Displays title
* **AddStudent.jsx** → Form to add students
* **StudentSummary.jsx** → Shows total, passed, average
* **AllDetails.jsx** → Displays student table and update functionality
* **App.jsx** → Main component managing state

---

## 🧠 Logic Used

* **useState** → Manage student data
* **map()** → Render student list
* **filter()** → Count passed students
* **reduce()** → Calculate average score
* **Controlled Inputs** → Handle user input

---

## ▶️ How to Run

```bash id="q1x8p7"
npm install
npm run dev
```

---

## 📌 Output

* Displays student records in tabular form
* Updates scores dynamically
* Summary section updates in real-time

---

## ⚠️ Notes

* Score should be between 0–100
* Pass condition: score ≥ 40
* Average is calculated using all student scores

---

## 👨‍🎓 Author

**Name:** Vedu
**Course:** Engineering
**Assignment:** React Student Dashboard

---
