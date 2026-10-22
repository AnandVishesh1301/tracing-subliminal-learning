# Tracing Subliminal Learning Through Pretraining

Project page for the paper by Angela Tang\*, Vishesh Anand\* and Gonçalo Paulo (\*equal contribution; EleutherAI SOAR).

Plain static HTML/CSS, no build step, served by GitHub Pages from `main` at the repo root.

```
index.html     the page (blog post with a paper header)
style.css      all styling
favicon.svg
figures/       2x PNGs rendered from the paper PDFs; og.png is the 1200x630 link preview
```

Preview locally: `python3 -m http.server 8000`, then open http://localhost:8000.

## Placeholders to fill at launch

- Link buttons in `index.html` (📄 Paper → arXiv, 💻 Code → GitHub, 🤗 Models & data → Hugging Face, 🎥 Video → YouTube, 🧵 Thread → X, 📝 Blog post): replace each `<span class="btn soon">` with `<a class="btn" href="...">`; drop the "Greyed links are coming soon" note once all are live. Use the unversioned arXiv `abs/` URL.
- BibTeX: replace `XXXX.XXXXX` with the arXiv ID.
- Scholar meta: add `citation_arxiv_id` and `citation_pdf_url`.
- Video: replace the `video placeholder` div with the YouTube iframe noted beside it.
- Custom domain: add a `CNAME` file and update `og:url` / `og:image` / `twitter:image`.

All numbers on the page come from the arXiv version of the paper.
