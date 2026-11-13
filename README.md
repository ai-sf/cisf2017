# CISF 2017

Static archive of the website of **CISF 2017** (Conferenza Italiana Studenti di Fisica, Bari, 11-14 May 2017), served at <https://ai-sf.it/cisf2017>.

The site was originally a PHP site on the old AISF hosting. This repository holds a static copy of its pages as they were rendered, with the parts that need a server removed. It is a frozen archive, not a live project:

- The pages are plain HTML in the repository root and are served directly from the `main` branch by GitHub Pages.
- `.nojekyll` must stay, so that GitHub Pages serves the folders as they are.
- The registration form, the registrations back office and the contact form (PHP, MySQL, PHPMailer) were not migrated: the event is over and they need a server. The footer keeps the association's contact addresses.
- Google Analytics and its cookie banner were removed.

## Editing

Edit the HTML files directly. Keep paths relative so that the site works under `/cisf2017/`.
