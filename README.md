# Personal Website for Pyae Sone Nyo Hmine

This repository contains the source code for your personal website.  It is a simple static site built using only HTML and CSS, so you can easily update it directly on GitHub.

## How to update the content

The website is split across two main files:

* **`index.html`** – contains all of the page content, including your biography, education, experience, skills, projects and contact information.  You can edit the text inside this file directly on GitHub to update your information or add new sections.  The résumé link at the bottom of the page embeds your CV as a Base64‑encoded PDF.  To replace it with a new CV, convert your PDF to a Base64 string (for example, using an online converter), and replace the string in the `href="data:application/pdf;base64,…"` attribute.
* **`style.css`** – defines the appearance of the site.  This file uses a minimal colour palette with a neutral base colour, a deep navy accent and a warm beige secondary tone based on design guidelines that recommend starting with a neutral background and adding a single accent colour【955104833211802†L249-L254】.  Headings use a serif font because serif designs convey reliability and formality【52069978946969†L115-L119】, while the body text uses a clean sans‑serif font for readability.  The hero banner image is embedded as a Base64‑encoded JPEG in the CSS to avoid storing binary files in the repository.  If you want to change the hero image, convert your new image to Base64 (using a tool such as [base64-image.de](https://www.base64-image.de/)) and replace the data inside the `background-image` property in the `.hero` class.

## Publishing with GitHub Pages

Because this repository is named `username.github.io`, GitHub automatically serves it as a GitHub Pages site.  After pushing your changes, your site will be available at:

```
https://pyae-sone-hmine.github.io/
```

GitHub Pages may take a few minutes to update after each commit.  You can monitor the status in the **Pages** section of the repository settings.