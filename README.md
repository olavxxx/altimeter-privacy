# Altimeter privacy site

Public GitHub Pages source for the Altimeter privacy policy.

**Live:** <https://olavxxx.github.io/altimeter-privacy/> (pending first publish)

Pages is deployed from `main` / root. First publish: create the public GitHub repository
`olavxxx/altimeter-privacy`, push this repository, then enable **Settings → Pages → Deploy from a
branch → main / (root)**. Verify HTTP 200, `olavamjelde@gmail.com`, and both language sections.

## Updating

`index.html` is the same file as `altimeter/store/privacy-policy.html`. When the policy changes:

1. Edit `altimeter/store/privacy-policy.html` and bump its date.
2. Copy it over `index.html` here.
3. Commit and push both repositories. Pages redeploys from `main` automatically.

Do not add analytics, external fonts, or scripts: the point of the page is the same as the app's —
nothing leaves the device.
