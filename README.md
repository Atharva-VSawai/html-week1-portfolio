# 📘 Project Documentation — HTML Portfolio (Week 1)

This documentation explains the concepts learned, project structure, setup process, and how all technical requirements were fulfilled for the Week 1 HTML portfolio assignment.

---

## 📌 Project Overview & Objectives

### Overview
This project is a **personal portfolio website** developed using **pure HTML5**. It presents my personal information, skills, and contact details in a structured and accessible format.

The website is built without CSS frameworks or JavaScript libraries, focusing only on **HTML fundamentals**.

### Objectives
- Understand how web pages are structured using HTML
- Practice writing semantic and accessible markup
- Learn how to create navigation, sections, and forms
- Organize a project using a clean folder structure
- Prepare for future integration of CSS and JavaScript

---

## 🛠️ Setup & Installation Instructions

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Atharva-VSawai/html-week1-portfolio.git

2️⃣ Open the Folder
cd html-week1-portfolio

3️⃣ Run the Website

Open index.html in any modern browser
OR

Use Live Server in VS Code for real-time preview

No additional dependencies or installations are required.

📁 Code Structure Explanation

The project follows a clean and organized structure:

html-week1-portfolio/
│
├── index.html        → Main HTML file containing the website structure
├── README.md         → Documentation and project explanation
├── images/           → Stores all images used in the website
│   ├── profile.jpg
│   ├── project_quickshow.png
│   ├── project_whatsapp.png
│   └── project_vibecode.png

File Purpose

index.html: Contains all website content and HTML structure

README.md: Explains the project, setup, and documentation

images/: Holds images used in the About and Projects sections

🧩 HTML Concepts Learned

This project demonstrates the following core HTML concepts:

1️⃣ HTML Document Structure

<!DOCTYPE html> defines the document as HTML5

<html>, <head>, <body> define the overall layout

2️⃣ Semantic HTML

Used meaningful tags to improve readability and accessibility:

<header> – Page heading and title

<nav> – Navigation menu

<main> – Main content of the page

<section> – Logical grouping of content

<footer> – Footer information

3️⃣ Text & Content Elements

Headings: <h1> to <h3>

Paragraphs: <p>

Lists: <ul>, <li>

4️⃣ Links & Navigation

Internal links using anchor tags:

<a href="#about">About</a>


Enables navigation between sections

5️⃣ Images

Images added using:

<img src="images/profile.jpg" alt="Profile Photo">


alt attribute used for accessibility

6️⃣ Forms

Contact form created using:

<form>, <input>, <textarea>, <button>

Input validation using:

required

type="email"

minlength

📄 Website Structure

The website is divided into the following sections:

🔹 Header & Navigation

Displays name and role

Contains internal navigation links

🔹 About Section

Personal introduction

Education and background

🔹 Skills Section

Lists technical skills using unordered lists

🔹 Projects Section

Showcases major projects with images and descriptions

🔹 Contact Section

Includes a contact form with validation

🔹 Footer

Displays GitHub link and credits

📸 Screenshots of Working Application

The following screenshots demonstrate functionality:

Homepage with navigation

About and Skills sections

Contact form validation

📁 All screenshots are stored inside the images/ folder

(You can add actual screenshots and reference them here.)

✅ Technical Requirements Fulfilled
🔹 Requirement 1: Create index.html with proper HTML5 structure

✔ Implemented using:

<!DOCTYPE html>
<html>
<head>...</head>
<body>...</body>
</html>

🔹 Requirement 2: Add at least 3 sections (About, Skills, Contact)

✔ Implemented using:

<section id="about">...</section>
<section id="skills">...</section>
<section id="contact">...</section>

🔹 Requirement 3: Use semantic HTML tags

✔ Used:

<header>

<nav>

<main>

<section>

<footer>

🔹 Requirement 4: Include a working contact form

✔ Implemented form with input validation:

<input type="email" required>
<textarea required minlength="10"></textarea>

🔹 Requirement 5: Add images with proper alt text

✔ Example:

<img src="images/profile.jpg" alt="Atharva Sawai profile photo">

🔹 Requirement 6: Implement internal navigation links

✔ Navigation uses:

<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#contact">Contact</a>

🧪 Testing & Validation
✔ Browser Testing

Tested in Chrome and Edge

Layout verified on mobile and desktop

✔ Form Validation

Prevents submission if fields are empty

Validates email format

✔ HTML Validation

Verified using: https://validator.w3.org/

No structural errors found

📌 GitHub Structure Verification

Required structure:

index.html
README.md
images/


✔ All required files and folders are present and organized correctly.

🚀 Conclusion

This project successfully demonstrates:

Proper HTML5 document structure

Semantic markup

Form handling

Image embedding

Navigation using anchor links

Clean project organization

It provides a strong foundation for adding CSS and JavaScript in future development phases.

📄 License

This project is open-source and available under the MIT License.


