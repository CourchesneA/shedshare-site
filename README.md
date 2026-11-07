# ShedShare site

Home page, privacy policy and terms of service of the ShedShare Android app, published with GitHub Pages.

- French (reference version): `index.html`, `privacy.html`, `terms.html`
- English: `en/index.html`, `en/privacy.html`, `en/terms.html`
- Styles and icons: `assets/`

The download button links to `releases/latest/download/ShedShare.apk`. To publish a new app version, raise `versionCode` in the app, build the signed release APK, and create a GitHub Release in this repository with the file attached as `ShedShare.apk`. The link then serves the new version.

Plain HTML and CSS, no build step. When you change a policy, change both languages and the date at the top of the page.

`googlee25b74cd10c92b81.html` is the Google Search Console ownership proof for the home page URL of the OAuth consent screen. Do not delete it.
