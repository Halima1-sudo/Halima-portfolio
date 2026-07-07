# Halima Yusuf Sani — Portfolio

A 13-page HTML & CSS portfolio built in blue and white for Halima Yusuf Sani —
Software Engineering student at Northwest University Kano and founder of
Rhazy Collection.

## Pages
1. index.html — Home
2. about.html — About Me
3. education.html — Education
4. skills.html — Skills
5. certificates.html — Certificates
6. business.html — Rhazy Collection (entrepreneurship)
7. projects.html — Projects
8. gallery.html — Gallery overview
9. gallery-fashion.html — Modest fashion gallery
10. gallery-skincare.html — Halal skin care gallery
11. interests.html — Interests
12. contact.html — Contact
13. thankyou.html — Thank you page

## File structure
All files sit at the same level (no subfolders) — this matches how they were
uploaded to GitHub. `index.html` links to `style.css` and each `.svg` directly.

## Replacing the placeholder images
No real photos were provided yet, so the site currently uses hand-made SVG
placeholders so nothing looks broken. Swap them out with real files any time:

| Placeholder file | Replace with |
|---|---|
| `portrait-placeholder.svg` | Your real photo (used on Home and About) |
| `certificate-placeholder.svg` | Your saved freeCodeCamp certificate PNG |
| `fashion-1.svg`, `fashion-2.svg`, `fashion-3.svg` | Rhazy Collection fashion photos |
| `skincare-1.svg`, `skincare-2.svg`, `skincare-3.svg` | Rhazy Collection skin care photos |

To replace an image: upload your new file (any name you like) into the repo,
then open the relevant `.html` file on GitHub and update the matching
`src="..."` in the `<img>` tag to point to your new filename.

## Running it locally
This is a plain static site — no build step. Just open `index.html` in a
browser, or serve the folder with any static server.

## Deploying to Vercel
1. Push this folder to a GitHub repository.
2. Go to vercel.com → **New Project** → import the repository.
3. Framework preset: **Other** (it's a static site — no build command needed,
   output directory is the project root).
4. Deploy. The included `vercel.json` handles clean URLs and a basic security
   header automatically.
