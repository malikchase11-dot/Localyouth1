LOCAL YOUTH — Mobile deploy package

1) Upload this repo to GitHub (upload ZIP or files via GitHub mobile web).
2) On Render.com, create a new Web Service -> Connect your GitHub repo.
   - Build command: npm install
   - Start command: npm start
3) In Render environment variables add:
   DATABASE_URL = <your full Neon connection string>
4) Deploy. Render will run npm install and start the server.
5) Your site will be live at the Render URL.

SECURITY: Keep your DATABASE_URL secret. Do NOT paste it into public places.
If this string was exposed, rotate the password in Neon dashboard.
