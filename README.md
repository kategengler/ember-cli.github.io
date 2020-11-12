# Legacy Ember CLI Website

This repository contains the built API documentation for `ember-cli`, and redirects that point the legacy URLs to [https://cli.emberjs.com](https://cli.emberjs.com)
The source code for the active CLI guides can be found [here](https://github.com/ember-learn/cli-guides).

# About the API docs

This repository's content is hosted via Netlify, and unlike the guides content which is redirected, the built API docs are still used in production.

## To update the API docs

1. Clone this repository
2. Clone https://github.com/ember-cli/ember-cli and `yarn install`
3. In `ember-cli`, run `npx yuidoc .` to generate the API docs
4. Copy the contents of the `docs` folder into the `api` folder of this website repo
5. Run the app locally with `http-server .` and make sure that they show up as they should
6. Open a PR to this repository
