# Walton STEM Academy: draft homepage

A single-page draft homepage. Plain HTML and CSS, no build step, no dependencies.

## Files

- `index.html` is the whole page. Edit text and links here.
- `assets/hero.jpg` is the full-screen photo at the top of the page.

## Common edits

- **Hero photo:** replace `assets/hero.jpg` with another image (about 2000 px wide, under 500 KB works well) or change the `src` on the `<img>` inside `.hero-media`.
- **Photo placeholders:** the gray boxes with a `photo` class are placeholders. Replace each `<div class="photo ...">` with an `<img src="assets/your-photo.jpg" alt="...">`.
- **Pathway descriptions:** the four "Description to come" lines under "Four pathways".
- **Dates:** the application timeline is a `<dl class="dates">` list.

## Publishing with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open Settings, then Pages.
3. Under Build and deployment, choose "Deploy from a branch", select `main` and `/ (root)`, and save.
4. The site appears at `https://<your-account>.github.io/<repo-name>/` after a minute or two.
5. To use your own domain, add it under Settings, then Pages, then Custom domain.

## Notes

- Get parent permission before publishing photos of students.
- The links in the navigation point to the existing waltonstem.com pages until those pages are rebuilt here.
