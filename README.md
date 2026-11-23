# sharifkhan96.github.io

Personal site. Plain HTML + CSS, with no build step.

## Deploy to GitHub Pages

1. Create a public repo named exactly `sharifkhan96.github.io`.
2. Push these files to its `main` branch:

   ```sh
   git init -b main
   git add .
   git commit -m "Initial site"
   git remote add origin git@github.com:sharifkhan96/sharifkhan96.github.io.git
   git push -u origin main
   ```

3. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the site is live at https://sharifkhan96.github.io

## Edit

Everything is in `index.html` (content) and `style.css` (look). Preview locally with:

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```
