# documentation template for teamtomo packages

This is a documentation template using *mkdocs-material*
for packages in the *teamtomo* organisation.

Source files for documentation are kept in the `docs` directory.

The action in `.github/workflows/build-and-deploy-docs.yml` will 
automatically publish docs from the `main` branch.

See the built site at [teamtomo.org/docs-template](https://teamtomo.org/docs-template/).

# Usage
Copy `mkdocs.yml` and the `.github/workflows/build-and-deploy-docs.yml`

To build documentation locally, run

```sh
mkdocs serve
```
