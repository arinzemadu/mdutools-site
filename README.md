# MDU Tools – Node/Express Site for Render

This is a tiny Node.js project that serves the MDU Tools marketing site using Express.

## Structure

- `server.js` – Express server that serves files from `/public`
- `public/index.html` – the actual website (all CSS and JS inline)
- `package.json` – Node project definition
- `render.yaml` – Render config for a Node web service

## Deploying to Render

1. Create a new Git repository and commit these files.
2. Push to GitHub / GitLab / Bitbucket.
3. In Render, click **New → Web Service** and connect the repo.
4. Use:
   - **Environment:** Node
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`

Render will install dependencies and start the Express server, which serves `public/index.html`.
