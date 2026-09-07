# Swipe — temporary site

A standalone one-screen Swipe site: nav, hero (headline + 3D mascot + email
signup) and a straight navy footer. Pure static HTML/CSS/JS, no build step.

## Forms
Two Netlify Forms, auto-detected at deploy:
- `email-signup` — hero email capture ("YOU'RE ON THE LIST.")
- `idea` — modal idea submission ("GOT IT. WE'RE ON THE MESS.")
Both submit via fetch for inline success; both include a honeypot (`bot-field`).
View submissions in Netlify → Forms.

## Publish
- Netlify → Add new site → Import from Git → this repo
- Build command: *(blank)*  ·  Publish directory: `.`
