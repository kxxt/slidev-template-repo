# slidev-template-repo

A template repo for slidev slides with automatic GitHub Pages deployment.

Example: https://kxxt.github.io/slidev-template-repo

## Features

- Deploys to GitHub Pages on push
- Uses [pnpm](https://pnpm.io/) for dependency management
- Generates a directory index for the slides

## Usage

1. Click the "Use this template" button to create a new repo
2. Clone the new repo
3. Change "workflow permissions" to "Read and write permission" in `Repo Settings` > `Actions` > `General`.
4. Enable the `deploy` workflow in GitHub Actions
5. Duplicate the `template` folder in the `slides` folder and rename it to your presentation name.
6. Edit the slides and optionally preview them locally with `pnpm -F <slide-subfolder-name> run dev` 
7. Commit your changes and push to GitHub
8. Wait for the `deploy` workflow to finish
9. Enable GitHub Pages on `gh-pages` branch
10. Visit your slides at `https://<your-username>.github.io/<your-repo-name>/<slide-subfolder>`
11. That's it!
