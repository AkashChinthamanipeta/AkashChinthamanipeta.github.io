# akashtechnologies.tech

Personal site of Akash Chinthamanipeta — robotics and automation engineer.
Static HTML/CSS, no build step, no dependencies.

## Pages

| File | Contents |
|---|---|
| `index.html` | Home — about, projects, contact |
| `publications.html` | IEEE papers, articles, technical writing |
| `talks.html` | Invited talks and presentations |
| `media.html` | Press and recognition |
| `service.html` | IEEE leadership, peer review, judging |

`assets/` holds the profile photo and resume PDF.

## Running locally

No tooling required — open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Deploying

Files are served from the repository root. `CNAME` points the custom
domain at GitHub Pages; delete it if you host elsewhere.

## License

Code is available under the MIT License. Written content, images, and
the resume are © Akash Chinthamanipeta — not licensed for reuse.
