<div align="center">

# Corporate website

**A four-page company site with placeholder content, built in WordPress with Elementor.**

[![Live demo](https://img.shields.io/badge/Live%20demo-open-2d4a7c?style=for-the-badge)](https://evanexanes.github.io/corporate-website/)
[![Case study](https://img.shields.io/badge/Case%20study-read-555555?style=for-the-badge)](https://evanexanes.github.io/02-case-study-corporate.html)

![WordPress](https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-92003B?logo=elementor&logoColor=white)
![Format](https://img.shields.io/badge/This%20repo-static%20export-555555)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-2d4a7c.svg)](LICENSE)

<img src="docs/screenshot.webp" alt="The corporate website home page" width="860">

</div>

## What this shows
- A WordPress build in Elementor on the OceanWP theme, from page layout to a static export that runs on GitHub Pages.
- Practice work with placeholder text, so it shows layout and build skills, not a real business.
- Every page is documented, with a page list and re-export steps in `docs/DOCUMENTATION.md`.

Lighthouse results for the live demo with mobile settings:

| Performance | Accessibility | Best practices | Largest contentful paint |
|---|---|---|---|
| 71 | 93 | 100 | 5.7 s |

Lighthouse 12.8.2, mobile settings with simulated throttling, median of three runs from a laptop on 10 November 2026. The performance score varied from 70 to 77 between runs. The home page transfers about 1.0 MB, down from about 1.5 MB before the uploaded images were converted to WebP. The SEO score is left out because these demo pages carry a `noindex` tag.

## Contents
- [What this shows](#what-this-shows)
- [About](#about)
- [Stack](#stack)
- [What this repository is](#what-this-repository-is)
- [What works in the static copy](#what-works-in-the-static-copy)
- [License](#license)
- [Author](#author)

## About
A four-page company site: Home, About, Services and Contact. The text is placeholder. It is a self-initiated WordPress practice build.

## Stack

| Part | Tool |
|---|---|
| CMS | WordPress |
| Page builder | Elementor |
| Theme | OceanWP |
| Forms | Contact Form 7, sent through Web3Forms in this copy |

## What this repository is
A static copy of the WordPress site, exported with Simply Static so it can run on GitHub Pages. It is generated HTML, CSS and JavaScript, not the WordPress source: there is no PHP, database or `wp-config.php` here.

Each exported page opens with a documentation header (program name, description, author and a history table). The files are generated, so they are not meant to be edited by hand: change the site in WordPress, export it again and add a history row. The page list, theme and plugins are in [docs/DOCUMENTATION.md](docs/DOCUMENTATION.md).

## What works in the static copy
GitHub Pages cannot run PHP, so anything that needs the WordPress server does not work in this copy. The contact form sends through Web3Forms instead of Contact Form 7.

## License
WordPress, the theme and the plugins are each released under the GNU General Public License, version 2 or later or version 3, as each one states. This repository as a whole is released under the [GNU General Public License, version 3](LICENSE), which all of them allow. The sample text and pictures are placeholder content for a practice build.

## Author
**Evan Prens P. Exanes** · [GitHub](https://github.com/evanexanes) · [Portfolio](https://evanexanes.github.io/) · [Contact](https://evanexanes.github.io/07-contact.html)
