# Scale Theory Website — Claude Code Instructions

## What this is

Plain static HTML site. No framework, no build step, no dependencies. GitHub Pages serves it directly from `main`.

The only file with real content is `privacy-policy/index.html`. The root `index.html` just redirects there.

## When to update the privacy policy

Only when something genuinely changes in the app:
- The app starts collecting new data (analytics SDK added, backend introduced, etc.)
- Contact email changes
- A legal requirement changes

This repo does not need to stay in sync with the ScaleTheory app repo on any schedule — changes here are always intentional and manual.

## Design conventions

- Pure HTML with inline `<style>` — no external stylesheets or frameworks
- System font stack (`-apple-system, BlinkMacSystemFont, ...`)
- Max content width: `680px`, centered
- Always update the effective date when the policy content changes
