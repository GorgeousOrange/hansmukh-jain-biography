# Sanhitasuri Pratishthacharya Hansmukh Jain — bilingual website

A responsive, static Hindi-first and English biographical archive. Designed for GitHub Pages.

## Files

- `index.html` — Hindi homepage
- `en.html` — English version
- `assets/css/style.css` — design and responsive layout
- `assets/js/site.js` — mobile navigation and current year
- `assets/images/` — add portraits, event photographs and scans here

## Preview locally

Open `index.html` in a browser. No build step or package installation is required. The Google Fonts are optional; the site falls back to system fonts if offline.

## Add images

The HTML currently expects these image files:

- `assets/images/portrait-main.jpg`
- `assets/images/gallery-01.jpg`
- `assets/images/award-01.jpg`
- `assets/images/book-01.jpg`

Replace the placeholder image files by adding your own images with exactly these names, or change the `src` paths in both HTML files. Use JPG, PNG or WebP. Keep image file sizes sensible (ideally under 1–2 MB each) and use descriptive alt text.

To add more gallery entries, copy a `<figure>` block in the gallery section and update its image path, alt text and caption.

## Publish on GitHub Pages

1. Create a public repository. For a user site, name it exactly `YOUR-USERNAME.github.io`.
2. Upload the contents of this folder to the repository root (not the enclosing folder).
3. In repository Settings → Pages, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
4. Wait for the Pages deployment. The site should appear at `https://YOUR-USERNAME.github.io/`.

For a project repository with a different name, GitHub Pages will publish at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Before making the website public

- Confirm the subject's permission and rights to publish portraits, award certificates, letters and other documents.
- Remove private phone numbers, email addresses, home details and signatures unless there is a clear reason and permission to publish them.
- Check every name, date, title, place and institution against the original records. The award and institution lists are transcribed from the supplied biographical profile and are not independently verified in this template.
- Add independent references for significant claims. A family-provided biography and certificates are primary sources; they are not substitutes for independent coverage.
- If the website is maintained by a relative or family member, disclose that relationship on an About / editorial policy page.
- Do not describe this as an official website unless the subject has authorised that status.

## Suggested next improvements

- Add a `sources.html` page with a bibliography and links to independent coverage.
- Add individual pages for books and major consecration events.
- Add captions and source credits for every photograph.
- Add a contact form only if you have a suitable privacy policy and a safe way to receive submissions.

## Editorial note

This is an independent biographical archive template. It is not affiliated with or endorsed by Wikipedia. The initial text is based on a biographical profile supplied by the family and should be checked and supplemented with independent sources.
