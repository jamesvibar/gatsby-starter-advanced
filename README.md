# Gatsby Advanced Starter
[![Netlify Status](https://api.netlify.com/api/v1/badges/3a08136d-50be-45db-a2c5-891090f6ec7f/deploy-status)](https://app.netlify.com/sites/hello4ks-x2a4/deploys)

This is a fork of _gatsby-advanced-starter_ with the same name.

To learn more about what this starter can do. Please visit [gatsby-advanced-starter](https://github.com/Vagr9K/gatsby-advanced-starter)

## What changed with this fork?

- ESLint React reconfiguration
- Husky pre-commit hook for linting (thanks to lint-staging)

## What else to add

- [ ] Setup codeclimate for code test
- [ ] Setup Cypress.IO basic test
- [ ] Setup CircleCI integration
- [x] Rework the current starter to use contentful (currently uses markdown)
- [x] Remove all ESLint errors
- [ ] Add a fancy readme.md
- [ ] Create a Netlify Page

## Getting Started

Install this starter (assuming [Gatsby](https://github.com/gatsbyjs/gatsby/) is installed and updated) by running from your CLI:

```sh
gatsby new YourProjectName https://github.com/Vagr9K/gatsby-advanced-starter
npm run develop # or gatsby develop
```

Or you can fork the project, make your changes there and merge new features when needed.

Alternatively:

```sh
git clone https://github.com/Vagr9K/gatsby-advanced-starter YourProjectName # Clone the project
cd YourProjectname
rm -rf .git # So you can have your own changes stored in VCS.
npm install # or yarn install
npm run develop # or gatsby develop
```

WARNING: Make sure to edit `static/robots.txt` to include your domain for the sitemap!
