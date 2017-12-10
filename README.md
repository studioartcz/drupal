# Quick development template on Drupal 8

inspired by [Thunder](https://www.drupal.org/project/thunder) and Acquia [Lightning](https://www.drupal.org/project/lightning).

## Usage

```
composer create-project studioartcz/drupal domain.local --stability dev --no-interaction
```

## What this stack solving?

- multi-language support by default (english is default)
- standard user roles setup (client / editor, seo analytic, administrator)
- forms solution
- error reporting for humans (sentry.io)
- the right development way (composer, assets, git)
- prepared for environments: localhost, stage, production
- development tools (webprofiler, twig debug - suggestions)
- fixed UX @ admin (chosen, admin toolbar, styles)
- deployment solution (docker, separated data from app, builds, ...)

## Used modules:

- Paragraphs
- Webform
- Chosen
- Raven
- Devel
- Config Split
- Config Read Only
- Stage File Proxy
- Admin Toolbar