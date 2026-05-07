# Contact-Lock Project Page

Static, anonymized project page for *Contact-Topology Lock-In in Trajectory
Diffusion Models* (project alias **Contact-Lock**).

## Files

- `index.html` --- the page itself; pulls Bulma, FontAwesome, and Academicons
  from public CDNs.
- `static/css/style.css` --- minimal custom styles on top of Bulma.
- `static/images/` --- five headline figures (probe transition, causal-bell,
  forward-vs-reverse SNR null, cross-scene control gap, cross-family lock-in
  window).
- `.nojekyll` --- forces GitHub Pages to serve files as-is (no Jekyll build).

## Local preview

```bash
cd webpage
python -m http.server 8000
# visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push the contents of `webpage/` to the root (or `docs/`) of an anonymous
   GitHub repository. Do **not** put the page in a repo whose name or owner
   leaks the authors during the review period.
2. In *Settings &rarr; Pages*, set the source to the appropriate branch and
   directory. The page will be served at
   `https://<owner>.github.io/<repo>/`.
3. The current paper footnote points to
   `https://contact-lock.github.io/contact-lock/`.

## Anonymity

- Authors are listed as "Anonymous Author(s)" with no affiliation.
- The only outbound link is the anonymous code drop at
  `https://anonymous.4open.science/r/contact-lock-C409`.
- The footer credits the page-template lineage, not the authors.
