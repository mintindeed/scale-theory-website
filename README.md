# Scale Theory — Website

GitHub Pages site for the [Scale Theory](https://github.com/mintindeed/scale-theory) iOS app.

Currently hosts one page: the app's privacy policy, required for App Store listing.

## Structure

```
index.html              — redirects to /privacy-policy/
privacy-policy/
  index.html            — the actual policy page
```

## Updating the privacy policy

Edit `privacy-policy/index.html` directly — it's plain HTML with inline CSS, no build step.

When you update the policy, also update the effective date near the top of the file:

```html
<p class="effective-date">Effective May 2, 2026</p>
```

## Deployment

Served via GitHub Pages from the `main` branch. Changes pushed to `main` go live automatically within a minute or two.

To configure Pages for a new fork: **Settings → Pages → Source: Deploy from branch → main / (root)**.
