# Lebo Shore – Online Shopping Web Project

A simple static website (HTML + CSS) about online shopping: an introduction page, research background, and findings.

## Project Structure

```text
    Home_Page.html
    Research.html
    Findings.html
    style.css
    img/
      Main.png
      logo.png
      ONLINE.mp4
      bright.png
      problem.png
      solution.png
      Picture1.jpg
      Picture2.png
      ... (other images)
```

## Pages

- **Home_Page.html** – Introduction, focus question, and hero image/video.
- **Research.html** – Problem → Solution → “Bright side” sections.
- **Findings.html** – Survey/diagram-based findings (includes Picture1 and Picture2).

All pages share the same layout elements:
- Fixed top navigation bar (logo + links)
- Shared stylesheet: `Website/style.css`
- Images/videos loaded from `Website/img/`

## How to Run / View

This is a static website.

1. Open **Website/Home_Page.html** in your browser.
2. Use the navigation links to view the other pages.

> Note: Because the site uses relative paths (e.g., `style.css`, `img/...`), it’s best to keep the full `Website/` folder together when viewing.

## Customization

- **Branding/Nav**: update `Website/style.css` and the `<img src="img/logo.png">` in each HTML page.
- **Content**: edit the relevant HTML files (`Home_Page.html`, `Research.html`, `Findings.html`).
- **Styles**: edit `Website/style.css`.
- **Media**: replace files inside `Website/img/` (keep filenames the same unless you also update the HTML).

## Credits

© 2026 Computer Science, Tech Panda (as shown in the footer of the pages).


