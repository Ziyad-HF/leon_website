# leon_website

A responsive, single-page agency landing page built with plain HTML and CSS.

## Overview

Leon is a static web template for a creative, minimal design agency. The page presents the agency's services, a portfolio, an about section and contact details in one scrolling layout. It uses no build step and no JavaScript, so it can be opened directly in a browser or hosted on any static host.

## Key features

- Single-page layout with anchor navigation (Services, Portfolio, About, Contact).
- Landing section with an intro message and a features strip.
- Services, portfolio and about sections.
- Contact section with a mailto link and social icons.
- Responsive styling using media queries at several breakpoints (767px, 991/992px and 1199/1200px).
- Pure HTML and CSS; no dependencies to install.

## Tech stack

- HTML5
- CSS3 (`css/leon.css`, with `css/normalize.css` as a reset)
- Font Awesome Free 6.4.0 (icons, bundled in `css/all.min.css` and `webfonts/`)
- Google Fonts: Work Sans (loaded from the Google Fonts CDN)

## Repository structure

```
leon_website/
├── index.html          # The page
├── css/
│   ├── leon.css        # Site styles
│   ├── normalize.css   # CSS reset
│   └── all.min.css     # Font Awesome stylesheet
├── images/             # Logo, portfolio and section images
└── webfonts/           # Font Awesome font files
```

## Installation

No installation is required.

```bash
git clone https://github.com/Ziyad-HF/leon_website.git
cd leon_website
```

## Usage

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

An internet connection is needed for the Work Sans font, which is loaded from Google Fonts.

## Data

The site contains no datasets. Images are stored in `images/`. Font Awesome Free is distributed under its own licenses (icons CC BY 4.0, fonts SIL OFL 1.1, code MIT), as stated in the header of `css/all.min.css`.

## Team / Credits

- Ziyad ElFayoumy ([Ziyad-HF](https://github.com/Ziyad-HF))

## License

Released under the MIT License. See [LICENSE](LICENSE). Bundled third-party assets (Font Awesome, normalize.css, Google Fonts) keep their own licenses.

## Contact

Ziyad ElFayoumy: [LinkedIn](https://www.linkedin.com/in/ziyad-el-fayoumy)
