# The CRISPR Index

A student-built biotechnology research platform focused on recent CRISPR and gene-editing research.

## Project structure

- `index.html` — website structure and content
- `styles.css` — all website styling
- `script.js` — paper library, student research guides, filters, expanded CRISPR Explorer, AI Tutor prototype, citations, contextual concept links, and animation
- `assets/daniel-profile.png` — profile image used in the About section

## Run locally

You can open `index.html` directly in a browser.

For the most reliable local preview, use a simple local server, for example with Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub will provide the public URL once the site is deployed.

## Note

The AI Tutor is a front-end educational prototype using the structured research data stored in `script.js`. It does not call a live AI API. It offers suggested questions and simple keyword-based follow-up routing, and it is intentionally conservative when source information is incomplete.

## Source-quality note

The V2 interface includes explicit source-status labels. Records that were not independently reconciled with their linked original source are marked for verification instead of being silently presented as fully verified bibliography. Missing DOI information is displayed as `DOI not available`.

## Original research links

Each paper in the research library now includes a **View original paper ↗** button. Links point to the publisher, DOI, PubMed, or an authoritative full-text repository where available.

