# Ankush — Polyinnovae AI Hackathon site

## Before deploying
1. Add your real photo as `photo.jpg` in this folder (square, decent resolution).
   In `index.html`, inside the `.photo-frame` div, replace the placeholder div with:
   `<img src="photo.jpg" alt="Ankush N R">`
2. Record a 60-second intro video, save as `intro.mp4` in this folder.
   In `index.html`, inside `.video-frame`, replace the placeholder div with:
   `<video controls src="intro.mp4"></video>`
3. Edit the "polymath" answer in the `#polymath` section so it's ~100 words and sounds like you, not me.
4. Delete the orange `devnote` banner block at the top of `index.html` (search `id="devnote"`).
5. `resume.pdf` is already in this folder — it's your latest resume, linked from the Resume section.

## Deploy to Vercel (fastest path — ~2 min)
Option A — CLI (recommended):
```
npm i -g vercel        # if you don't have it
cd polymath-site
vercel --prod
```
It'll ask you to log in via browser (GitHub/Google/email) the first time, then give you a live `*.vercel.app` URL immediately.

Option B — Drag and drop:
1. Go to vercel.com → sign in → "Add New Project" → "Deploy" tab → drag this whole folder in.
2. Copy the live URL it gives you.

## Then
Paste that `*.vercel.app` URL into the Polyinnovae AI registration form's "Your Vercel link" field.
