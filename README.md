# slidev-template-repo

A template repo for slidev slides which deploys to github pages on push.

Example: https://kxxt.github.io/slidev-template-repo

## Features

- Deploys to GitHub Pages on push
- Uses [pnpm](https://pnpm.io/) for dependency management
- Generates a directory index for the slides

## Usage

1. Click the "Use this template" button to create a new repo
2. Clone the new repo
3. Enable the `deploy` workflow in GitHub Actions
4. Duplicate the `template` folder in the `slides` folder and rename it to your presentation name.
5. Edit the slides and optionally preview them locally with `pnpm -F <slide-subfolder-name> run dev` 
6. Commit your changes and push to GitHub
7. Wait for the `deploy` workflow to finish
8. Enable GitHub Pages on `gh-pages` branch
9. Visit your slides at `https://<your-username>.github.io/<your-repo-name>/<slide-subfolder>`
10. That's it!
