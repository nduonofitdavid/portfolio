# Personal portfolio

A quiet, single-page portfolio, with a white background, black text, and a clear monospace typeface. Built with HTML and CSS; no JavaScript, dependencies, or build step.

## Preview

Open `index.html` in a browser, or serve this folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Make it yours

Edit `index.html` to replace the placeholder name, page title, description, introduction, and interests. Update the email, LinkedIn, and GitHub destinations in the footer.

Experience appears above projects. Each entry is a `<li>` inside `.experience-list`; replace the placeholder role, organization, dates, and short description. Duplicate or remove an entry as needed.

Each project is a `<li>` inside `.project-list`. Replace its name, one-line description, and `href`. Duplicate or remove a `<li>` to change the number of projects. Project links currently use `example.com` as placeholders.

Adjust the font size, column width, and spacing in `style.css`.

## Font

The page uses **JetBrains Mono Regular**, bundled locally in `fonts/JetBrainsMono-Regular.ttf`, at 17px with generous line spacing. Its SIL Open Font License is included in `fonts/JetBrainsMono-OFL.txt`. It falls back to Consolas, Liberation Mono, or the browser's monospace font.
