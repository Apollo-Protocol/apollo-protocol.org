![Apollo Protocol Logo](https://raw.githubusercontent.com/Apollo-Protocol/.github/main/profile/apollo-protocol-logo.png#gh-light-mode-only)
![Apollo Protocol Logo](https://raw.githubusercontent.com/Apollo-Protocol/.github/main/profile/apollo-protocol-logo-dark-mode.png#gh-dark-mode-only)

This repository powers the website delivered at https://apollo-protocol.org.
It uses `pug` as a templating language, which is built out using `npm run build`. This produces a `dist` folder with the static HTML/CSS.

The repo is configured to serve the `gh-pages` branch as GitHub Pages.
The domain apollo-protocol is pointed at the GitHub servers.

An action (`.github/workflows/build-and-deploy.yml`) is defined that automatically builds the repo and then pushes the results onto the `gh-pages` branch.
