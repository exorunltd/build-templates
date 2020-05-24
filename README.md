# Exorun build-templates

This community-based project contains all build templates on [exorun.io](https://www.exorun.io/).

# Usage

Each template (under ./templates) can be used from the [exorun CLI](https://www.npmjs.com/package/exorun-cli):

- _exorun template [template name]_: Try to automatically find an appropriate template and generate a Dockerfile. If a template is specified, it is used directly.
- _exorun list-templates_: List all available templates.

# Contributing

Users are highly welcomed to contribute to this project. You fined tune a Dockerfile for your own needs? Perhaps other users are interested to use your Dockerfile. Feel free to contribute!

- Fork this project.
- Commit and push in the forked project.
- Create a pull request from the forked project.

Make sure to follow our convention:

- Create a repository under templates using downcase name.
- Provide a Dockerfile
- Make sure to use WORKDIR /opt/app
- Make sure to expose port 80
- Provide a README.md

See several examples in the templates folder.
