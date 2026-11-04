# VaniOS

My personal website, a 2007-style desktop. Open the windows, drag them around, close them all, and have some chai.

It's a single static page (`index.html`) with no build step and no backend.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Edit

- **Email:** set `MAIL` at the top of the script in `index.html`.
- **Projects:** edit the `REPOS` list in the same script.
- **Windows:** each window is a `<section class="win">` in `index.html`.

## Art credits (public domain)

- Wallpaper: *The Ninth Wave*, Ivan Aivazovsky, 1850 (pixelated)
- Paint window: *Shakuntala*, Raja Ravi Varma
- `assets/vani.svg`: an original illustration made for this site
