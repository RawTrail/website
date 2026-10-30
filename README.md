# RawTrail website

The marketing site for [RawTrail](https://github.com/RawTrail/RawTrail). It is plain HTML and CSS with no build step and no JavaScript, served by GitHub Pages from the root of `main` at https://rawtrail.io.

## Editing

Edit `index.html` and `style.css`, then push to `main`. Pages redeploys in about a minute. To preview locally, run `python3 -m http.server 8000` and open http://localhost:8000.

`og.png` is the social card, rendered from `og.svg`. After changing the SVG, regenerate it with `rsvg-convert -w 1200 -h 630 og.svg -o og.png`.

`.well-known/security.txt` has an `Expires` date that must be renewed once a year (RFC 9116).

## License

MIT, see [LICENSE](LICENSE).
