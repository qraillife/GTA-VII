# Grand Theft Auto VII — concept site

Static single-page site. No build step, no dependencies, no framework.

## Deploy
1. Create a public repo on GitHub.
2. Upload `index.html`, `README.md` and the `assets/` folder (keep the folder name).
3. Settings → Pages → Source: *Deploy from a branch* → `main` → `/ (root)` → Save.
4. Live at `https://<user>.github.io/<repo>/` within a minute.

## Making the trailer real
Drop an MP4 at `assets/trailer.mp4`. To use YouTube instead, replace the `<video>` element in the
`#trailerModal` block with an iframe:

<iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe>

## Notes
- Fonts come from Google Fonts (Bodoni Moda, Archivo). Both fall back to system faces offline.
- The signup form is front-end only — point it at Formspree or Netlify Forms to make it live.
- Fan project. GTA and Rockstar Games are trademarks of Take-Two Interactive.
