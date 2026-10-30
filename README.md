# The Devinals Vinyl Player

A static, mobile-friendly vinyl player for GitHub Pages. No external libraries or backend.

## Add music

1. Create a `music` folder in this repository.
2. Upload recordings you own or have permission to distribute, such as `music/first-song.mp3`.
3. Edit `tracks.json` to list only Devinals tracks:

```json
[
  {"title":"First Song", "file":"music/first-song.mp3"},
  {"title":"Second Song", "file":"music/second-song.mp3"}
]
```

Use the actual song titles and filenames. No recordings are bundled.

## Publish on GitHub Pages

1. Create a public GitHub repository, for example `devinals-vinyl`.
2. Upload `index.html`, `tracks.json`, and the `music` folder.
3. Go to **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Visit `https://YOUR-USERNAME.github.io/devinals-vinyl/` once deployment finishes.

Note: GitHub Pages sites are publicly accessible. Do not upload music without distribution rights. GitHub also has repository/file size limits; use suitably compressed audio.
