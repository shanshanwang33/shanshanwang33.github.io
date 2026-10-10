# Shanshan Wang — academic website

The academic website of Shanshan Wang, Assistant Professor of Statistics at Western Michigan University.

Website: https://shanshanwang33.github.io

## Content

- `_pages/about.md`: introduction and research interests
- `_pages/research.md`: publications, manuscripts, software, presentations, and conference service
- `_pages/teaching.md`: courses and terms
- `_pages/more-about-me.md`: education, certifications, and a link to the full CV
- `_pages/contact.md`: email, phone, office, mailing address, and professional profiles
- `files/Shanshan_Wang_CV.pdf`: downloadable CV, updated September 2026
- `_config.yml`: site identity and professional links
- `_data/navigation.yml`: navigation
- `assets/css/main.scss`: layout and styling

Update the December 2026 and Spring 2027 upcoming labels when those events have passed. Publication statuses should also be maintained. Replace `files/Shanshan_Wang_CV.pdf` to update the downloadable CV.

The profile currently uses an SW initials image. To add a portrait, upload it to `images/` and set `author.avatar` in `_config.yml` to its filename.

## Run locally

Install Ruby 3.3 and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --host localhost --port 4000
```

Open http://localhost:4000. To produce a static build:

```sh
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
```

## Publish

The public repository `shanshanwang33/shanshanwang33.github.io` publishes from `main` and `/ (root)` using GitHub Pages. Changes pushed to `main` are built and deployed automatically.

The site uses Jekyll with the standard GitHub Pages plugin set. Navigation, profile links, and light/dark theme switching use local JavaScript. There are no analytics trackers or third-party font requests.

## License and attribution

The upstream MIT license is preserved in `LICENSE`. The site uses [Academic Pages](https://github.com/academicpages/academicpages.github.io), which derives from Minimal Mistakes, with Jekyll.
