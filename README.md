# Typelevel Steward

Runs the [scala-steward-action](https://github.com/scala-steward-org/scala-steward-action) daily to update the dependencies of Typelevel projects.  Pull requests are opened by the [typelevel-steward app](https://github.com/organizations/typelevel/settings/apps/typelevel-steward).

## Adding a repo

- Repositories with less than 20 parallel jobs that take less than 20 minutes each should be added to `cheap-ci.md`
- Repositories with more than 20 parallel jobs or jobs that take more than 20 minutes should be added to `expensive-ci.md`

This action uses a GitHub token for the Typelevel installation of typelevel-steward and will only work on projects in the Typelevel org.  For external projects, see [diy-steward](https://github.com/armanbilge/diy-steward/).
