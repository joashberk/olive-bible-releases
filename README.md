# Olive Bible content releases

Approved content for the Olive Bible app. Each release is a git tag (`vYYYY.MM.DD`). `latest.json` on the main
branch names the newest one. Files are served by jsDelivr:

    https://cdn.jsdelivr.net/gh/joashberk/olive-bible-releases@<tag>/data/bible/index.json

The `data/` folder has the same layout and file shapes as the app's own `data/` folder. Every version of every olive
stays available at `data/olives/<id>/v<N>.json`, so a correction never rewrites what someone already studied.

Only content a person approved is here. Credits the sources require are in `data/credits.json`.
