# Utopia Photo Booth

A lightweight browser-based photo booth built for events, exhibitions, and interactive installations.

Utopia Photo Booth provides a simple and accessible way to create themed photo strip experiences directly in the browser. Users can capture photos using their device camera, preview the final composition in real time, and instantly download the generated photo strip without requiring a backend server.

Designed originally for a campus movie festival booth, the project has been refactored into a reusable open-source web application suitable for public events, student projects, and creative activations.

---

## Features

* Browser-based camera capture
* Three-photo strip workflow
* Multiple themed photo frames
* Real-time preview
* Instant image export and download
* Manual image upload support
* Lightweight static deployment
* Mobile and desktop browser compatible

---

## Demo

**https://yiyu0501.github.io/photobooth_yiyu/**

This project can be deployed easily using:

* GitHub Pages
* Netlify
* Vercel
* Any static web hosting service

---

## Project Structure

```text
photobooth_yiyu/
├── index.html
├── README.md
└── images/
    ├── 01.png.png
    ├── 02.png.png
    ├── 03.png.png
    ├── moviefest.png
    ├── xiaogou.png
    └── xiaomao.png
```

---

## Included Assets

The `images/` directory contains several themed frame templates used by the photo booth interface.

Current assets include:

* `01.png.png`
* `02.png.png`
* `03.png.png`
* `moviefest.png`
* `xiaogou.png`
* `xiaomao.png`

You may freely replace these assets with your own frame designs.
If filenames are modified, update the corresponding paths inside `index.html`.

---

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/yiyu0501/photobooth_yiyu.git
```

### 2. Open the project

Simply open:

```text
index.html
```

in your browser.

No build process or package installation is required.

---

## GitHub Pages Deployment

### Enable GitHub Pages

1. Open your repository on GitHub
2. Navigate to **Settings → Pages**
3. Under **Build and deployment**

   * Source → `Deploy from a branch`
   * Branch → `main`
   * Folder → `/ (root)`
4. Save the configuration

GitHub will automatically generate a public deployment URL.

---

## Usage Flow

1. Open the application
2. Allow camera permissions
3. Select a frame template
4. Capture three photos
5. Preview the final composition
6. Download the generated photo strip

---

## Customization

### Replace Frames

Add new PNG frame templates inside the `images/` folder.

### Modify Layout

The layout and rendering behavior can be customized directly inside:

```text
index.html
```

### Event Branding

You can easily adapt the project for:

* School events
* Brand activations
* Exhibitions
* Pop-up installations
* Fan events
* Community activities

---

## Technical Notes

* This project is fully front-end based
* No database or backend server required
* Works best in modern Chromium-based browsers
* Camera access requires HTTPS in most browsers

---

## Future Improvements

Potential future features include:

* GIF export
* QR code download sharing
* Multi-language support
* Cloud image storage
* Animated frame support
* Touchscreen kiosk mode
* Countdown sound effects

---

## Contributing

Contributions, improvements, and feature suggestions are welcome.

Feel free to fork the repository and submit pull requests.

---

## License

Please add your preferred open-source license.

Recommended options:

* MIT License
* Apache 2.0
* GPL v3

---

## Acknowledgements

Created for a university event photo booth experience and later adapted into an open-source interactive web project.
