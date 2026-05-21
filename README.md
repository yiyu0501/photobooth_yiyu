# Utopia Photo Booth

A browser-based photo booth built for a campus music and movie festival booth.

This project lets visitors take a 3-shot photo strip in the browser, apply themed frames, preview the final result, and download the finished image. It was originally built by a student team for a real school event, so the focus is practical use: fast setup, simple workflow, and easy deployment.

## Live demo

If you deploy this repository with GitHub Pages and keep `index.html` in the project root, the direct link is:

**https://yiyu0501.github.io/photobooth/**

## What it does

- Opens the camera directly in the browser
- Supports a 3-shot photo strip workflow
- Lets users switch between preset themed frames
- Shows live preview and final composite preview
- Downloads the final photo strip as an image
- Includes a staff mode for frame management and on-site operation
- Supports uploading photos as an alternative to live capture

## Included frames

This package includes 4 ready-to-use frames in the `images/` folder:

- `frame.png`
- `01.png.png`
- `02.png.png`
- `03.png.png`

The code is already set up to load these four files automatically.

## Project structure

```text
photobooth_ready/
├── index.html
├── README.md
└── images/
    ├── frame.png
    ├── 01.png.png
    ├── 02.png.png
    └── 03.png.png
```

## Quick start

1. Upload `index.html`, `README.md`, and the whole `images/` folder to your GitHub repository root.
2. In GitHub, go to **Settings → Pages**.
3. Set the source to **Deploy from a branch**.
4. Choose **main** branch and **/(root)** folder.
5. Save and wait for GitHub Pages to finish deploying.
6. Open your site link.

## How to use

1. Open the page on a tablet, laptop, or desktop browser.
2. Allow camera access.
3. Choose one of the preset frames.
4. Start the capture flow.
5. Take 3 photos or upload photos manually.
6. Review the final strip.
7. Download the result.

## Notes

- The frame images are expected to stay inside the `images/` folder.
- If you rename the frame files, update the file paths in `index.html`.
- For the cleanest public link, keep the main file name as `index.html`.

## About this project

This is not a commercial booth system. It is a student-built web photo booth made for a real campus event, then refined into a public project that other people can test, reuse, and adapt for their own booths or events.
