# Alexander Coque — Portfolio

Static, no-build website (plain HTML/CSS). Open `index.html` in a browser to preview.

## Replacing the sample content

- **Profile photo (homepage)**: in `index.html`, find the `<img src="https://i.pravatar.cc/560?img=13" ...>` inside `.hero-portrait` and replace the `src` with `assets/pictures/your-photo.jpg` after adding your photo to `assets/pictures/`.
- **Project photos**: each project card in `index.html` / `projects.html` has an `<img src="https://picsum.photos/seed/...">`. Replace those `src` values the same way once you've added your own images to `assets/pictures/`.
- **Resume**: drop your PDF at `assets/resumes/resume.pdf` (exact filename) — the Download button and preview note on `resume.html` are already wired to that path.
- **Bio, education, experience, contact details**: all plain text inside `about.html`, `education.html`, `experience.html`, and `contact.html` — search for the sample text and swap it in.
- **Contact form**: currently a visual-only placeholder. Connect it to a service like Formspree, or your own backend, before publishing.

## Hosting

This is fully static — you can drag the folder into Netlify/Vercel, push it to GitHub Pages, or upload it to any web host.
