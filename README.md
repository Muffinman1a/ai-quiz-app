# AI Knowledge Quiz

A simple 3-question AI trivia quiz. Mobile-first, no backend, single HTML file.

## Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New Project**
3. Import the GitHub repo (or drag-and-drop the `quiz-app/` folder)
4. Vercel auto-detects it as a static site — click **Deploy**
5. Your quiz is live at `https://your-project.vercel.app`

## Live edit on stage (the demo moment)

To add a feature live during the presentation, open `index.html` in Cursor and make the change. Suggested live edits:

- **Dark mode already works** — just show the toggle
- **Add confetti on any score** (not just perfect): change `if (perfect)` to `if (score > 0)` in `renderResults()`
- **Change button colour**: find `bg-indigo-600` and change to `bg-violet-600` or `bg-emerald-600`
- **Add a timer**: add a countdown timer to each question for extra pressure

After editing, push to GitHub — Vercel redeploys automatically in ~10 seconds.

## Keyboard shortcuts

Users can press **1, 2, 3, or 4** to select an answer without using the mouse.
