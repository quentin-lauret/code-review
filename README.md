# Rubber Duck – legal pages

Static pages for the Rubber Duck iOS app, served by GitHub Pages.

- `privacy/index.html`: Privacy Policy (App Store guideline 5.1.1).

## Preview locally

```sh
python3 -m http.server 8000   # then open http://localhost:8000/privacy/
```

## Publish

GitHub Pages, branch `main`, folder `/` (root). Free Pages requires the repo to be public.
URL: https://quentin-lauret.github.io/code-review/privacy/

Use that URL in App Store Connect (Privacy Policy URL) and in the app (`MockData.privacyURL` in rubber-duck).
