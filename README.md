# yiyangshao2003.github.io

Personal homepage. Plain HTML and CSS, served by GitHub Pages from `master` (no build step; `.nojekyll` turns Jekyll off).

| Path | What it is |
| --- | --- |
| `index.html` | Homepage: intro, links, publications |
| `archive/index.html` | Archive: earlier projects and the RoboMaster documentary |
| `archive/quadcopter/index.html` | Unlisted page (not linked, `noindex`) |
| `assets/style.css` | All styles, light and dark |
| `assets/media/` | Paper teaser videos (`.mp4`) and posters (`.jpg`); archive images in `projects/` |
| `files/cv.pdf` | CV — replace this file to update it; the link stays the same |

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Add a paper

Copy one `<article class="row">` block in `index.html`. Put the year in the `label` div only for the first paper of that year.
Teaser videos: about 10–15 s, muted, 800×450, H.264. For example:

```sh
ffmpeg -i in.mp4 -an -t 12 -vf "scale=800:450,fps=30,format=yuv420p" -c:v libx264 -preset slow -crf 26 -movflags +faststart assets/media/name.mp4
ffmpeg -ss 2 -i assets/media/name.mp4 -frames:v 1 -q:v 4 assets/media/name.jpg
```
