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

## Content

The body text and figures (`figures/lw_fig1.png` … `lw_fig4.png`) mirror the [LessWrong post](https://www.lesswrong.com/posts/53XwjN2gAKzjKCp5s/tracing-subliminal-learning-through-pretraining) verbatim; change them there first, then here. The BibTeX is arXiv's own export for 2610.30884.

## Still to fill

- Link buttons in `index.html` (💻 Code → GitHub, 🤗 Models & data → Hugging Face, 🧵 Thread → X): replace each `<span class="btn soon">` with `<a class="btn" href="...">`.
- Custom domain: add a `CNAME` file and update `og:url` / `og:image` / `twitter:image`.
