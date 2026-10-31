# Pathfinder — Student Skills & Internship Tracker

A beginner-friendly React app that helps students keep track of skills they are building and discover sample internships. Created as a Group 7 project for an eight-student team.

## What it does

- See a starter set of skills and update progress in 5% steps.
- Add a new skill with a category using the form.
- Search and filter sample internships by role, company, skill, or field.
- Save opportunities and mark applications as sent; totals update on screen.
- Use the responsive dashboard on a phone or desktop.

This is a front-end prototype. Sample internships are fictional, and actions are only kept in the current browser session; there is no login, database, or real application submission.

## Run it on your computer

1. Install Node.js (the LTS version) from [nodejs.org](https://nodejs.org/).
2. Open a terminal in this project folder.
3. Run `npm install` once, then `npm run dev`.
4. Open the local address shown in the terminal, usually `http://localhost:5173`.

To create a production build, run `npm run build`. The generated files go into `dist/`.

## Upload this project using the GitHub website

1. Sign in at [github.com](https://github.com/) and choose **+ → New repository**.
2. Name it `student-skills-internship-tracker`, choose **Public** or **Private**, and create the repository. For a simple source upload, leave “Add a README” unchecked.
3. If you downloaded this project as a ZIP, extract it first. Open the project folder and select its contents—not the outer folder and not `node_modules`.
4. In the new repository, choose **Add file → Upload files**. Drag the project files and the `src` folder into the upload area, or use the file chooser. Include `README.md`, `package.json`, `index.html`, `.gitignore`, `vite.config.js`, and `src/`.
5. Enter a commit message such as `Add Pathfinder React project`, then click **Commit changes**.

Do not upload `node_modules` or `dist`; these are generated and ignored. Uploading to GitHub stores the source code but does not run the app. For a live demo later, connect the repository to a host such as GitHub Pages or Vercel.

## Suggested team split (8 students)

1. Project coordination and README; 2. dashboard and navigation; 3. skills data and progress controls; 4. add-skill form; 5. internship cards and filters; 6. application/save interactions; 7. responsive styling and accessibility; 8. testing, presentation, and future features.

## Tech

React, JavaScript, Vite, and CSS. No external UI library is required.
