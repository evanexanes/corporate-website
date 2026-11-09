# Corporate Website: documentation

This repository is a static export of a WordPress practice site, hosted on GitHub Pages at
<https://evanexanes.github.io/corporate-website/>. It holds generated HTML, CSS and JavaScript only: there is no
PHP, database or `wp-config.php`. See the [README](../README.md) for the overview and licence.

## Stack

| Part | Tool |
|---|---|
| CMS | WordPress |
| Page builder | Elementor |
| Theme | OceanWP |
| Forms | Contact Form 7, sent through Web3Forms in this copy |

## Theme and plugins in the export

- Theme: `oceanwp`
- Plugin folders under `wp-content/plugins/`: `all-in-one-wp-migration`, `contact-form-7`, `elementor`, `ocean-extra`, `pro-elements`, `simply-static`

These are third-party WordPress files under their own GPL licences and are not edited by hand.

## Pages

Every page below opens with a documentation header: program name, description, author and a
history table. 7 pages.

| File | Page title |
|---|---|
| `about/index.html` | About |
| `author/corporate/index.html` | corporate |
| `category/uncategorized/index.html` | Uncategorized |
| `contact/index.html` | Contact |
| `hello-world/index.html` | Hello world! |
| `index.html` | Corporate Website |
| `services/index.html` | Services |

## Changing the site

1. Edit the page in WordPress.
2. Export the site again with Simply Static and replace the generated files.
3. A re-export overwrites the pages and removes their headers. Put the header back and add a history
   row with the date, a description of 32 characters or fewer, and `EPPE`.

## Change history

| Date | Description | Programmer name |
|---|---|---|
| 09/28/2026 | Initial Implementation | EPPE |
| 11/10/2026 | Added file headers and docs | EPPE |
