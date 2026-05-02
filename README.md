# Şükrü Tarık Kostak Personal Website

Static personal portfolio website based on `CV_KOSTAK.pdf`.

## Structure

- `index.html` - main landing page
- `styles.css` - shared visual system and responsive layout
- `script.js` - mobile menu and reveal animations
- `projects/` - project case study pages
- `assets/cv.png` - top profile image
- `CV_KOSTAK.pdf` - downloadable CV

## Publishing With GitHub Pages

1. Create a GitHub repository.
2. Upload this folder to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Set source to `Deploy from a branch`.
5. Select `main` branch and `/root`.
6. Save.

The site will work without a build step because it uses plain HTML, CSS, and JavaScript.

## Adding Profile Image

Put your top profile image at:

```text
assets/cv.png
```

The homepage already points to this file in the `hero-portrait` section.

## Adding Project Media

Create an asset folder for each project, for example:

```text
assets/stealth-ucav/
assets/fastener-selection/
assets/local-deepsearch/
assets/shell-eco-marathon/
```

Then replace the placeholder blocks in the related `projects/*.html` file with images or file links.
