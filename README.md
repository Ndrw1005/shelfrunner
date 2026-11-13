# ShelfRunner public release

This repository contains only the production site and its GitHub Pages workflow. The editable project, review tools, exports and private research remain outside this repository.

To update: build the project locally with `npm run build`, review the production `dist` artifact, replace this repository's `site` directory with that artifact, then commit and push to the same repository. The workflow deploys `site` to GitHub Pages. Configure Settings → Pages → Build and deployment → Source as GitHub Actions.
