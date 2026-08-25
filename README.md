# 📝 Student Feedback Survey Form

A simple, pure HTML survey form created to collect feedback from students about their courses, experience, and satisfaction level. This project focuses on using **HTML5 form elements correctly** — no CSS, no JavaScript, just clean and accessible HTML.

---

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Form Fields Overview](#form-fields-overview)
- [Project Structure](#project-structure)
- [How to Run This Project](#how-to-run-this-project)
- [How Form Submission Works](#how-form-submission-works)
- [Accessibility](#accessibility)
- [Screenshots](#screenshots)
- [Future Improvements](#future-improvements)
- [Author](#author)

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
