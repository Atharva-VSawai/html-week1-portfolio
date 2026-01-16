# Personal Portfolio — Atharva Sawai

This is a Week 1 HTML portfolio project created as part of an HTML fundamentals course.  
It showcases personal information, skills, and selected projects. The content is populated from my resume and GitHub profile.

## Live preview
Open `index.html` in your browser or use the VS Code Live Server extension.

## Project structure
index.html
css/styles.css
images/
README.md

## About the content
- Name: **Atharva Sawai**
- Education: Bachelor of Computer Engineering (Honors in Data Science) — Dr. D.Y. Patil College of Engineering (Expected 2027)
- Selected Projects: QuickShow, WhatsApp Clone, Vibecode Editor (project details from resume).
  - Resume file used for content: included in the repo (or referenced). See the PDF used in development. :contentReference[oaicite:2]{index=2}
- GitHub profile: https://github.com/Atharva-VSawai. :contentReference[oaicite:3]{index=3}

## Setup instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/html-week1-portfolio.git
   cd html-week1-portfolio
2. Add images inside images/ (profile and project screenshots).

3. Open index.html in a browser, or:

4. Use VS Code: install Live Server extension and click Go Live.

5. (Optional) Add CSS in css/styles.css to customize appearance.


---

# 4) Daily Step-by-Step Guide (expanded)
Day-by-day actions to complete the Week 1 assignment — follow this checklist.

**Day 1 — Setup & Basic Structure**
- Install VS Code.
- Create project folder, initialize `git` repo.
- Create `index.html`, add HTML5 `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.
- Implement header with your name & nav links.

**Day 2 — Header & Navigation**
- Build header with `<nav>` and internal links to `#about`, `#skills`, `#projects`, `#contact`.
- Test anchor jumps in browser.

**Day 3 — About Section**
- Write a 2–3 paragraph bio using resume summary (you can copy/shorten from resume). Mention education and contact email.
- Add a `profile.jpg` into `images/` and reference it with `alt` text.

**Day 4 — Skills Section**
- Add a list of skills using `<ul>` and `<li>` (semantic).
- Consider two columns using CSS `columns` or grid.

**Day 5 — Contact Section**
- Build a contact form with `input` (name, email, subject) and `textarea` (message).
- Add `required`, `type="email"`, `minlength` attributes.
- Add a small JS script that prevents empty/invalid submission in demo.

**Day 6 — Images & Links**
- Add screenshots for projects in `images/`.
- Add external links (GitHub profile, LinkedIn). Use `rel="noopener"` and `target="_blank"` for external links.

**Day 7 — Testing & Validation**
- Test in Chrome/Firefox: responsive checkpoints.
- Run W3C validator and fix any structural errors.
- Keyboard/Accessibility check (tab order, alt text, semantic headings).

---

# 5) Submission & Documentation Requirements (what to include in your GitHub repo)

- `index.html` (required)
- `README.md` (required)
- `images/` folder with `profile.jpg` and project screenshots (required)
- `css/styles.css` (optional but recommended)
- `requirements.txt` (optional — not needed here)
- A short `Documentation.md` or extended README section describing:
  - What HTML concepts you learned (list them),
  - How the portfolio is structured (list file/sections),
  - How to run/test/validate the site (W3C, Live Server),
  - Screenshots demonstrating functionality (place in `screenshots/` or `images/`).

---

# 6) Quality Standards Checklist (to get full marks)
Make sure each item is ticked before submission:

- [ ] `index.html` exists and uses HTML5 `<!DOCTYPE html>`.
- [ ] Contains at least 3 sections: **About**, **Skills**, **Contact**.
- [ ] Semantic tags used: `header`, `nav`, `main`, `section`, `footer`.
- [ ] Internal navigation links working.
- [ ] Contact form is present and uses `required` attributes and `type="email"`.
- [ ] Images included with descriptive `alt` text.
- [ ] Code organized into folders: `images/`, `css/`, `js/`.
- [ ] `README.md` contains project overview, setup instructions and contact info.
- [ ] HTML validated with W3C Markup Validator (fix all errors).
- [ ] Screenshots are included in the repo demonstrating the website on desktop and mobile widths.
- [ ] Commit history with clear messages (e.g., `init: add index.html`, `feat: add contact form`).

---

# 7) Testing & Validation (concrete steps)
1. **Open locally**: double-click `index.html` or use Live Server in VS Code.
2. **Form validation**:
   - Leave fields blank and press *Send Message* — browser should show required field errors.
   - Enter invalid email, ensure browser prevents submit.
3. **W3C validator**:
   - Go to https://validator.w3.org/
   - Upload `index.html` or paste the URL (if hosted) and fix any errors reported.
4. **Accessibility quick checks**:
   - Tab through the page. Verify focus order.
   - Images have `alt` text.
   - Use browser dev tools to simulate mobile sizes.
5. **Cross-browser**:
   - Open in Chrome and Firefox and check layout and form behavior.

---

# 8) How I used your resume & GitHub (what I pulled in)
- Resume provided project descriptions, summary, and skills — I used those verbatim (shortened where necessary) to populate About, Skills, and Projects. :contentReference[oaicite:4]{index=4}
- GitHub profile shows your README and top repositories (e.g., `PW-Assignments`, `Awesome-JavaScript-Interviews`, etc.). I referenced this so the Projects section lists QuickShow, WhatsApp Clone, Vibecode (from resume) and links to your GitHub. :contentReference[oaicite:5]{index=5}

---

# 9) Optional `requirements.txt`
Not required for a static HTML project. If you later add a simple backend for form handling (Python Flask, Node), add dependencies here. Example placeholder:



