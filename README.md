# Tunify

Tunify is an Android music player build with ad breaks removed from the playback flow. This repository hosts the project website and the signed APK.

## Website

`index.html` is a standalone page with no build step, framework, or CDN dependency. GitHub Pages can serve it directly from the repository root.

The Download buttons use `./Tunify.apk`, so the file comes from this repository when the site runs on GitHub Pages.

## APK

- File: `Tunify.apk`
- Package: `com.sahil.devx.tunify`
- Version: `2.6.0` (code `63`)
- Minimum Android: 8.0 (API 26)
- SHA-256: `e2117eb760c64047a3234b89d0db2fc4e8b2587481eb03c5836be37fb4dfc7d5`

Made by Sahil Chaudhary. Follow [@sahil.devx](https://www.instagram.com/sahil.devx/) on Instagram.

## Local preview

```bash
python3 -m http.server 8000 --directory .
```

Open `http://localhost:8000/`. The same relative APK link works locally and on GitHub Pages.
