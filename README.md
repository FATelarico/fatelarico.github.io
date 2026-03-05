<div align="center">
<h3>This repository contains the source for my personal website, published via GitHub Pages.</h3>
<br>
<p align="center">
  <a href="https://www.fatelarico.eu" target="_self"><img src="https://img.shields.io/badge/website-ONLINE-brightgreen"></a>
&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="http://docs.webstudio.is/" target="_blank">
    <img src="https://img.shields.io/badge/Built%20with%20%20-WebStudio-purple?logo=webtrees"/>
  </a>
</p>
<br>
<!-- <img src="https://webstudio.is/cgi/image/edge-fade_Q5hCdQXL2Rs1eMfLYFB0x.png?width=1920&quality=80&format=auto"> -->
<!-- <img width="1920" height="500" alt="image" src="https://github.com/user-attachments/assets/cd2d1ce1-92a3-4ac3-86f2-891f340dfe16" /> -->
<img height="315" alt="image" src="https://github.com/user-attachments/assets/6e0dd4a9-0dc5-4ee3-9796-63cf0309e614" />
</div>
<hr>

## What’s in here

This is a static site (plain HTML/CSS/JS + assets). The current structure is intentionally simple:

- `index.html` — homepage
- `my-work/index.html` — “My Work” section/page
- `assets/` — images, generated CSS, and other static assets
- `CNAME` — custom domain configuration for GitHub Pages (`www.fatelarico.eu`)
- `PrivacyPolicy.md` — privacy policy (linked from the site)
- `robots.txt` — currently disallows all crawlers
- `LICENSE` — content licence for this repository

## Local preview

Because this is static HTML, you can preview it with any local web server.

Option A (Python):

```bash
python -m http.server 8000
```
Then open [`http://localhost:8000`](http://localhost:8000).

Option B (Node):

```bash
npx serve .
```

## Deployment

Deployment is handled by GitHub Pages: pushing to main updates the published site (subject to Pages build propagation).

## Licence

Unless stated otherwise, the website content in this repository is licensed under the terms in LICENSE (Creative Commons BY-NC-SA 4.0).

## Contact

See the “Contact” section on the website, or the details in [`PrivacyPolicy.md`](https://github.com/FATelarico/fatelarico.github.io/blob/6813b70c473b7b9dc2228e7c4b2e0992926365f4/PrivacyPolicy.md)
