# repeated — landing page

Early-access landing page for [repeated](https://repeated.to), the social
network you speak. Static site, GitHub Pages.

- `index.html` — the page. Self-contained: the hero mark draws itself in a
  canvas (same relief algorithm as the app icon); waitlist form writes to the
  `waitlist` collection in the `repeated-to` Firebase project (create-only
  security rules); GA4 via the "repeated landing" web app config inline.
- `privacy.html` / `delete-account.html` — the compliance URLs referenced by
  the Play Data Safety form and AppHive.
- `CNAME` — custom domain for GitHub Pages (`repeated.to`).

The icon/mark generator lives in the app repo under `docs/icon/`.
