# Roselle

A soft, floral-inspired personal homepage built with HTML and Tailwind CSS.

## Preview

Install the local Tailwind CSS dependency and build the stylesheet:

```powershell
npm install
npm run build
```

Then start a local server from the project directory:

```powershell
python -m http.server 5500
```

Then visit [http://localhost:5500](http://localhost:5500).

The generated `styles.css` is included in the repository so the published page does not need the Tailwind CDN or Node.js at runtime. Run `npm run build` again after changing Tailwind classes or the styles in `src/input.css`. The page's photos still load from Unsplash.
