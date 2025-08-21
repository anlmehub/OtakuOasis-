# OtakuOasis

Website + REST API for anime.  
Runs with Node.js + Express + MongoDB (optional).

## Run locally
npm install
npm start

## Deploy to Render
- Push repo to GitHub
- Connect repo to Render
- Add env vars in Render dashboard:
  - PORT = 10000
  - MONGODB_URI = your MongoDB URI (or leave empty for memory mode)
  - OWNER_TOKEN = secure token
