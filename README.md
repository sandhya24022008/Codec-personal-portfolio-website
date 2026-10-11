# Personal Portfolio Website

A responsive portfolio starter built with HTML, CSS, JavaScript, Node.js, Express, and MongoDB. It includes profile, skills, projects, and a contact form.

## Requirements
- Node.js 18+
- MongoDB local instance or MongoDB Atlas (optional for viewing the static site)

## Run locally
1. Extract this ZIP.
2. Open the extracted `personal-portfolio-website` folder in VS Code.
3. Install Node.js if it is not installed.
4. Open a terminal in this folder and run `npm install`.
5. Copy `.env.example` to `.env`.
6. Add your MongoDB connection string to `MONGODB_URI` in `.env`.
7. Run `npm start`.
8. Visit `http://localhost:3000`.

The frontend loads with demo content even if the database is not connected. API endpoints return stored data when MongoDB is available.

## API endpoints
- `GET /api/health`
- `GET /api/profile`
- `GET /api/projects`
- `GET /api/skills`
- `POST /api/contact`

## GitHub upload (web browser)
1. Open your existing GitHub repository.
2. Tap **Add file** → **Upload files**.
3. Extract this ZIP first. Upload the files and folders *inside* the extracted project folder, not the ZIP itself.
4. Wait until file names appear in the upload area.
5. Enter a commit message such as `Add portfolio website project`.
6. Tap **Commit changes**.

Do not upload `.env` or `node_modules`. `.gitignore` excludes them automatically when using Git.

## Personalize it
Edit `public/index.html` and `public/js/app.js` to change your name, summary, skills, and projects. This is a starter template; replace the demo text with your real details before publishing.

## Deploy
For a live site, deploy the Node.js app to a Node-compatible host and set environment variables in that host's dashboard. GitHub stores your code but does not run this Express backend by itself.