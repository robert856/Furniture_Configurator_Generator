# Furniture Configurator

A standalone browser furniture configurator. `Configurator_v28.html` is the original uploaded application; `index.html` opens it from the site root.

## Run locally

Requires Python 3 and a modern browser. No package installation or build is needed.

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

Open the server in your browser. The application embeds its furniture artwork and color palette, so the separate assets folders and JSON files are not required for this version. Google Fonts are optional; system fonts work when they are unavailable.

## Features

Choose furniture components, colors and hardware finishes, switch designs, randomize configurations, generate color scenes, view a bill of materials, and export images.

AI Render is optional and requires your own Google Gemini API key, entered in the application. It sends the captured design and prompt to Google's API and requires Internet access. Never commit API keys to Git.

## Hosting

Serve this directory with any static web server. For GitHub Pages, select the `main` branch and repository root in the repository's Pages settings.
