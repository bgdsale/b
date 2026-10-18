# RootTutor landing page

Static sales page for Android root tutorial / paid access landing page.

## Local preview

```bash
cd pretty-site
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Push the project to a GitHub repository.
2. In GitHub, open Settings → Pages.
3. Set Source to GitHub Actions.
4. Commit the workflow file in `.github/workflows/pages.yml`.
5. Push to `main` and GitHub will deploy automatically.

## Files

- `index.html` — page structure and content
- `styles.css` — visual design and animations
- `main.js` — menu toggle and scroll reveal
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow

## Important

This project is a static front-end only. There is no backend or payment processing built in. The purchase button currently opens the Telegram channel:

```text
https://t.me/stnboost
```
