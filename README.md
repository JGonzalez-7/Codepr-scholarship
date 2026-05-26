# Codepr Scholarship

A static website for the Holberton Puerto Rico Scholarship Fund. The site shares scholarship fund information, donation links, student outcomes, news PDFs, and donor benefit information.

## Project Structure

```text
Codepr-scholarship/
├── index.html          # Main scholarship landing page
├── act22.html          # Donor benefits page
├── css/
│   ├── style.css       # Main site styles
│   └── placeholders.css
├── pics/               # Images used by the site
├── news/               # News article PDFs
└── video.mp4           # Scholarship fund video
```

## Requirements

No build step or package installation is required. You only need a web browser.

The pages load some dependencies from CDNs, so an internet connection is recommended:

- Bootstrap 5 CSS and JavaScript
- Google Fonts
- Adobe Typekit
- Font Awesome

## How to Run

### Option 1: Open the HTML file directly

From the repository folder, open `index.html` in your browser.

```bash
cd Codepr-scholarship
```

Then double-click `index.html`, or open it from your browser with `File > Open File`.

### Option 2: Run a local static server

This is the recommended option because it serves the site the same way a simple web host would.

```bash
cd Codepr-scholarship
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

To stop the server, press `Ctrl+C` in the terminal.

## Pages

- `index.html`: Main page with fund overview, achievements, career success stories, news, and donation call-to-action.
- `act22.html`: Donor benefits page with donation methods and Act 22 information.

## Notes for Editing

- Update visual styling in `css/style.css`.
- Add or replace images in `pics/`, then reference them from the HTML.
- Add news PDFs to `news/`, then link to them from the news section in `index.html`.
- Donation buttons currently point to `https://www.fcpr.org/donations/iachep/`.
