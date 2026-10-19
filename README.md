# Dexterity Event Registration Page

A simple, mobile-first, responsive static website (HTML + CSS, no build tools) that lists
departments, their events, and a **Register** text link for each event.

## Structure
```
├── index.html        # Page content: poster, departments, events, links
├── style.css         # All styling (colors/fonts at the top in :root)
└── assets/
    └── poster.svg    # Placeholder - replace with your poster image
```

## How to edit
1. **Poster** – put your image in `assets/` (e.g. `poster.jpg`) and change `src="assets/poster.svg"` in `index.html`.
2. **Event names** – replace `Event Name 1` etc. in `index.html`.
3. **Register links** – replace `href="#"` with the real registration URL.
4. **Add an event** – copy one `<li>...</li>` line inside a department.
5. **Add a department** – copy one whole `<section class="dept">...</section>` block.
6. **Colors / fonts** – edit the variables at the top of `style.css`.

## Run locally
Open `index.html` in a browser (or run `python3 -m http.server`).

## Publish free on GitHub Pages
1. Push this folder to a new GitHub repo.
2. Repo **Settings → Pages**.
3. Source: **Deploy from a branch** → `main` → `/ (root)` → Save.
4. Your site goes live at `https://<username>.github.io/<repo-name>/`.
