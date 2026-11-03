# scripts/

Not part of the published site (excluded in `_config.yml`).

## `og-image.html`

Source of the social preview banner `images/og-image.png` (1200x630), the image
shown when a link to the site is shared (LinkedIn, Slack, X, …).
Edit the HTML, then render it with headless Chrome from the repository root:

```
google-chrome --headless=new --hide-scrollbars --allow-file-access-from-files \
  --window-size=1200,630 --virtual-time-budget=5000 \
  --screenshot=images/og-image.png "file://$PWD/scripts/og-image.html"
```
