# Annotated Notes

A static website of interactive presentation slides paired with detailed
speaker notes and annotations. Inspired by
[Simon Willison's annotated talks](https://simonwillison.net/tags/annotated-talks/).

## Talks

- **Error Culture** — PyCascades 2025. What the heck are all of these error
  emails for anyway? An exploration of error monitoring, alert fatigue, and
  building a healthy error culture in your development team.
  ([`pycascades-2025/`](pycascades-2025/index.html))
- **Contributing to Django** — DjangoCon US 2023. How I learned to stop
  worrying and just try to fix an ORM bug. A journey through contributing to
  Django for the first time, from intimidation to implementation.
  ([`dcus-2023/`](dcus-2023/index.html))

## Structure

```
.
├── index.html          # Landing page linking to each annotated talk
├── styles.css          # Shared styles for the landing page
├── pycascades-2025/    # "Error Culture" slides + notes
└── dcus-2023/          # "Contributing to Django" slides + notes
```

## Viewing locally

It's plain static HTML — open `index.html` in a browser, or serve the
directory:

```bash
python -m http.server
```

Then visit http://localhost:8000.

## License

See [LICENSE](LICENSE).

Made by [Ryan Cheley](https://ryancheley.com/).
