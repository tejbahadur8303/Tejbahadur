# Tejbahadur | Portfolio

Personal portfolio website of **Tejbahadur**, Fullstack Developer from Ghaziabad, India.
Flutter apps, MERN platforms and trading simulations.

A plain static site: **HTML + CSS only**, no build step, no dependencies.

## Sections

- **Hero**: intro, role, call-to-action buttons and portrait
- **About**: short bio and quick facts
- **Skills**: Frontend, Mobile, Backend and Data, AI and Simulation
- **Projects**: EduMind AI, HackTrack, MediKiosk, QuantArena, SaveMitra, Smart Rural, Student360, SyncPay, TechClub, TeleReply
- **Contact**: GitHub, LinkedIn, LeetCode, CodeChef, GeeksforGeeks and email

## Project structure

```
.
├── index.html
├── style.css
├── README.md
└── assets/
    └── photo.jpg
```

## Run locally

Just open `index.html` in a browser.

Or serve it with a tiny local server:

```bash
python3 -m http.server 5500
```

Then visit <http://localhost:5500>.

## Deploy

**Vercel**

1. Push this folder to a GitHub repo.
2. In Vercel, choose **Add New → Project** and import the repo.
3. Set **Framework Preset** to **Other**. Leave Build Command and Output Directory empty.
4. Deploy. `index.html` must sit at the repo root.

**GitHub Pages**

1. Open the repo **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`.
3. Save. The site goes live at `https://<username>.github.io/<repo>/`.

## Customize

- **Text and projects**: edit `index.html`. Each project is one `<article class="card project">` block.
- **Colors and fonts**: change the variables at the top of `style.css` (`--cy`, `--vi`, `--pk`, `--bg`).
- **Photo**: replace `assets/photo.jpg` with your own (about 300 × 350 px works well).
- **Add a live link to a project**: add `<a class="link" href="URL" target="_blank" rel="noopener">Open live site &rarr;</a>` inside its card.

## Tech

HTML5 · CSS3 (grid, flexbox, custom properties) · Google Fonts (Space Grotesk, JetBrains Mono)

## Contact

- GitHub: [tejbahadur8303](https://github.com/tejbahadur8303)
- LinkedIn: [tejbahadur8303](https://www.linkedin.com/in/tejbahadur8303/)
- LeetCode: [tej8303](https://leetcode.com/u/tej8303/)
- CodeChef: [tejbahadur8303](https://www.codechef.com/users/tejbahadur8303)
- GeeksforGeeks: [tejbahadur8303](https://www.geeksforgeeks.org/profile/tejbahadur8303)
- Email: tej9519@gmail.com
