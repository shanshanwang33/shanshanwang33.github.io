# Shanshan Wang — academic website

A personal academic website based on [Academic Pages](https://github.com/academicpages/academicpages.github.io) and Jekyll, customized for Shanshan Wang, Assistant Professor of Statistics at Western Michigan University.

Intended address: https://shanshanwang33.github.io

## Content

- `_pages/about.md`: introduction, research interests, recent and upcoming activities, contact
- `_pages/research.md`: publications, manuscripts, and software
- `_pages/teaching.md`: courses and terms
- `_pages/talks.md`: presentations and conference service
- `_pages/cv.md`: complete web CV
- `_config.yml`: site identity and professional links
- `_data/navigation.yml`: navigation
- `_sass/_custom.scss`: responsive visual design

Content is based on the supplied CV updated September 2026. Events are labeled relative to October 9, 2026; update the December 2026 and Spring 2027 labels when those events have passed. Publication statuses should also be maintained. The original private CV file and phone number are not part of this repository.

No headshot was supplied; the site uses a typographic monogram. To add a portrait, replace the monogram in `_includes/author-profile.html` with an appropriately described image.

## Run locally

Install Ruby 3.3 and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Open http://127.0.0.1:4000. To produce a static build:

```sh
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
```

## Publish

Use a public repository named `shanshanwang33.github.io` owned by `shanshanwang33`. Push this source to its `main` branch. In Settings → Pages, select **Deploy from a branch**, then choose `main` and `/ (root)`. GitHub Pages builds the Jekyll website after each push to `main`; no separate workflow setup is needed.

The source uses the standard GitHub Pages plugin set and contains no custom plugins, secrets, analytics trackers, or third-party font requests. The mobile menu is a native HTML disclosure and works without JavaScript.

## License and attribution

The upstream MIT license is preserved in `LICENSE`. Site footer credits Academic Pages and Jekyll. Academic Pages derives from Minimal Mistakes.
