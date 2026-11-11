# Walton STEM Academy: draft homepage

A single-page draft homepage. Plain HTML and CSS, no build step, no dependencies.

## Files

- `index.html` is the whole page. Edit text and links here.
- `hero.jpg` is the full-screen photo at the top of the page.
- can upload more photo files, then follow below instructions to make the appear in the frames

## Common edits

- **Hero photo:** replace `hero.jpg` with another image (about 2000 px wide, under 500 KB works well) or change the `src` on the `<img>` inside `.hero-media`.
- **Photo placeholders:** the gray boxes with a `photo` class are placeholders. Replace each `<div class="photo ...">` with an `<img src="assets/your-photo.jpg" alt="...">`.
- **Pathway descriptions:** the four "Description to come" lines under "Four pathways".
- **Dates:** the application timeline is a `<dl class="dates">` list.

## Publishing with GitHub Pages

1. Push this folder to a GitHub repository.
2. Make a pull request with new or updated code, apporver will merge the pull request back into main
3. To use our own domain, we can add it under Settings, then Pages, then Custom domain.

## Notes

- The links in the navigation point to the existing waltonstem.com pages until those pages are rebuilt here.
