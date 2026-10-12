# Emigraphix Studio — migration snapshot

This repository contains the existing single-file HTML/CSS/JavaScript Emigraphix Studio prototype. It is a prototype, not a fully functioning image editor.

## Run
Open index.html in a modern browser or serve it locally (e.g. python -m http.server 8000).

## Migration rules
- Preserve currently working features and mobile-first UI.
- Do not rebuild from scratch or overwrite the existing design.
- First run the imported app and take a baseline screenshot.
- Fix existing text moving/transforms and shape bugs before adding new tools.
- Incrementally separate modules, using version control and tests.
- Browser project storage is local to each origin; previously saved browser projects are not automatically transferred to a new host.
