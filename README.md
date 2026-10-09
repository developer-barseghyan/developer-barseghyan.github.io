# developer-barseghyan.github.io

Home page for Tigran Barseghyan's apps, served at https://developer-barseghyan.github.io/

- `index.html`: the app list, with links to each app's support site (its own repo, served under `/<repo>/`).
- `app-ads.txt`: authorised ad sellers for AdMob. Must stay at the root.
- `assets/icons/`: app icons at 240 px, from each Xcode project's AppIcon.
- `assets/og.png`: link preview image (1200 x 630).

Adding an app: copy one `<article class="app">` block in `index.html`, add its icon to
`assets/icons/`, its support repo's three URLs to `sitemap.xml`, and an entry to the
JSON-LD list at the top. When an app goes live, replace its `Coming soon` chip with the
App Store badge block from an app that already has one, using the app's
`https://apps.apple.com/app/id…` link.
