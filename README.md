# .github

The GitHub organisation profile for **FindsYou** — the README shown at
[github.com/FindsYou-Work](https://github.com/FindsYou-Work), and the artwork
behind it.

```
profile/README.md      the org profile page
assets/org-banner.png  the header image, rendered from tools/org-banner.html
assets/logo.svg        the mark — things fall, one is caught
assets/logo.png        512px square, for the org avatar
tools/org-banner.html  source for the banner
tools/render.sh        regenerates both PNGs with headless Chrome
```

## Regenerating the artwork

ImageMagick cannot rasterize these (webfonts, CSS gradients), so Chrome does the
work. Both PNGs render at 2x and are committed.

```sh
./tools/render.sh
```

## The avatar

GitHub has no API for organisation avatars. Upload `assets/logo.png` by hand at
[the org profile settings](https://github.com/organizations/FindsYou-Work/settings/profile).
