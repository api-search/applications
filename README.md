# APIs.io Applications

Source of https://apis.io/applications/: what the leading apps in 90 categories are built on, joined to the APIs.io catalog.

Nothing here is edited by hand. `network/scripts/build_applications.py` writes `_applications/`, `_data/applications.yml`, `shared-layer.md`, `index.html`, the section layouts and `applications/api/applications.json`. `network/scripts/bootstrap-sites.py` writes `_config.yml`, `_includes/`, `assets/`, the nav and `default.html`.

The records are in `planning/application-blueprints`. The design is `site/DESIGN.md` there.

Per-category JSON is on the Understanding plan and is served by the API, never from this repo.

Blueprints are CC BY-NC-SA 4.0. See LICENSE-NOTE.md.
