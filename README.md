# Selena Dang — Portfolio

A responsive personal portfolio with About, Academic Projects, Technical Experience, Leadership, and Contact pages.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --directory dist
```

Then open http://localhost:8000. No dependency installation or build step is required.

## Project files

- `dist/index.html`: page shell and navigation
- `dist/content.js`: biography, projects, experience, leadership, and links
- `dist/app.js`: page rendering and interactions
- `dist/style.css`: responsive styling
- `dist/assets/`: original photos, PDF reports, presentations, résumé, and recording

The contact form opens the visitor's email application; it does not send email through a server.

## Hosting

Deploy the `dist` folder to a static website host. The existing Sites publication is managed separately. Its repository credentials and Git history are not included in this export.

## Content rights

Personal portfolio content and supplied media are included for this portfolio. No open-source license is granted for third-party logos, group photographs, company reports, or other supplied materials.
