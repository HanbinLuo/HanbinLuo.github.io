# Hanbin Luo's Homepage

This repository contains the source for my GitHub Pages personal homepage:

https://HanbinLuo.github.io

The site is based on [senli1073/academic-homepage-template](https://github.com/senli1073/academic-homepage-template). Content is stored as Markdown files under `contents/` and loaded directly by `index.html`, so no build step is required.

## Local Preview

```powershell
python -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

## Deployment

Create a public GitHub repository named `HanbinLuo.github.io`, then push this repository's `main` branch. GitHub Pages will publish the site at `https://HanbinLuo.github.io`.
