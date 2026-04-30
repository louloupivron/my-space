# my-space

JupyterLite on GitHub Pages (Pyodide kernel) for Python notebooks, including NIfTI examples with **itkwidgets**.

Open the deployed site and run notebooks under **content/**.

## Try it (after deploy)

Use your repo’s **GitHub Pages** URL, or see the upstream demo: [jupyterlite.github.io/demo](https://jupyterlite.github.io/demo).

## Requirements (browsers)

- Firefox 90+
- Chromium 89+

## Deploy

[Deploy JupyterLite on GitHub Pages](https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html) — this repo uses **GitHub Actions** (see `.github/workflows/deploy.yml`).

See [`requirements.txt`](requirements.txt) for build dependencies (includes **imjoy-jupyterlab-extension** for itkwidgets in the browser build).
