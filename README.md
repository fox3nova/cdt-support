# CDT App Store Support Site

Static support and privacy pages for App Store submission.

## Files

- `index.html` - support/privacy landing page
- `support/index.html` - App Store Support URL target
- `privacy/index.html` - App Store Privacy Policy URL target
- `assets/styles.css` - shared CDT-style CSS
- `assets/cdt_icon_dark.png` - app icon asset copied from the app catalog

## App Store Connect URLs

After publishing with GitHub Pages, use these values in App Store Connect:

- Support URL: `https://<github-pages-base>/support/`
- Privacy Policy URL: `https://<github-pages-base>/privacy/`

Examples:

- User/organization site: `https://<username>.github.io/cdt/support/`
- Project Pages site: `https://<username>.github.io/<repo>/support/`
- Custom domain: `https://<domain>/support/`

## Before publishing

- Replace the support contact note in `support/index.html` with the public support email or contact method.
- Confirm the final GitHub Pages base URL.
- Open `index.html`, `support/index.html`, and `privacy/index.html` in a browser and verify layout on mobile and desktop widths.
