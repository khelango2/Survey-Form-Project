# 📝 Student Feedback Survey Form

A simple, pure HTML survey form created to collect feedback from students about their courses, experience, and satisfaction level. This project focuses on using **HTML5 form elements correctly** — no CSS, no JavaScript, just clean and accessible HTML.

---

## 📋 Table of Contents
- [About the Project](#-about-the-project) 
- [Tech Stack](#%EF%B8%8F-tech-stack)
- [Features](#-features)
- [Form Fields Overview](#-form-fields-overview)
- [Project Structure](#-project-structure)
- [How to Run This Project](#-how-to-run-this-project)
- [How Form Submission Works](#-how-form-submission-works)

---

## 📖 About the Project

This is a beginner-to-intermediate level HTML project built to practice and demonstrate different types of HTML form elements in one single page. The form is designed like a real-world student feedback survey — collecting personal details, preferences, ratings, and written feedback.

The goal of this project is to show a solid understanding of:
- HTML form structure
- Different input types
- Native browser validation
- Accessible, semantic markup

No styling (CSS) or scripting (JavaScript) is used — everything you see is achieved purely with HTML.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and form elements only |

---

## ✨ Features

- Multiple input types: text, email, tel, date, number, range, file
- Grouped radio buttons and checkboxes using `<fieldset>` and `<legend>`
- Dropdown selection using `<select>`
- Multi-line feedback using `<textarea>`
- Built-in browser validation (no JavaScript needed) using:
  - `required`
  - `pattern`
  - `min` / `max`
  - `type="email"`, `type="tel"`, etc.
- Fully keyboard-navigable form (default HTML behavior)
- Clean and readable code structure

---

## 📊 Form Fields Overview

| # | Field | HTML Element | Description |
|---|---|---|---|
| 1 | Full Name | `<input type="text">` | Required field for student's name |
| 2 | Email Address | `<input type="email">` | Validated automatically by the browser |
| 3 | Phone Number | `<input type="tel">` | Validated using a `pattern` (10-digit format) |
| 4 | Survey Date | `<input type="date">` | Native calendar date picker |
| 5 | Age | `<input type="number">` | Restricted using `min` and `max` |
| 6 | Gender | Radio buttons | Options: Male / Female / Other |
| 7 | Hobbies | Checkboxes | Multiple selection: Reading, Sports, Music, Coding |
| 8 | Course / Age Group | `<select>` dropdown | Single choice selection |
| 9 | Satisfaction Level | Radio buttons | Options: Excellent / Good / Average / Poor |
| 10 | Service Rating | `<input type="range">` or `<input type="number">` | Rating scale from 1 to 10 |
| 11 | Upload Document | `<input type="file">` | Optional file upload field |
| 12 | Feedback | `<textarea>` | Multi-line text box for suggestions |
| 13 | Reset Button | `<input type="reset">` | Clears all entered data |
| 14 | Submit Button | `<input type="submit">` | Submits the form |

---

## 📁 Project Structure

survey-form-project/
├── index.html → Main HTML file containing the form
└── README.md → Project documentation (this file)


---

## 🚀 How to Run This Project

You don't need any server, installation, or setup. Just follow these steps:

## 🌐 Live Demo

👉 [View Live Form]( https://khelango2.github.io/Survey-Form-Project/)

---

##How to Run This Project Locally

1. Go to the repository: [https://github.com/KHELANGO2/survey](https://github.com/KHELANGO2/survey)
2. Click on `index.html`
3. Click the **Copy raw file** button (top-right of the code view) to copy all the code
4. On your computer, create a new file and name it `index.html`
5. Paste the copied code into it and save
6. Double-click `index.html` — it opens directly in your web browser
7. Fill out the form and click **Submit** to see the data appear in the URL

---

## 🔄 How Form Submission Works

Since this is a pure HTML project with no backend server, the form uses:

```html
<form method="GET">
```

- `method="GET"` means the data you enter gets attached to the page's URL as a query string when you click Submit
- No `action` attribute is used, which means the form submits to the same page you're already on
- After submitting, look at your browser's address bar — you'll see your entered data appended there, like:

- 
This is a simple way to visually confirm that your form is capturing and sending the correct data, without needing any backend or server-side code.

---


