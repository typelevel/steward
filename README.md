# Typelevel Steward

Runs the [scala-steward-action](https://github.com/scala-steward-org/scala-steward-action) daily to update the dependencies of Typelevel projects.  Pull requests are opened by the [typelevel-steward app](https://github.com/organizations/typelevel/settings/apps/typelevel-steward).

## Adding a repo

Edit the [repos.md](https://github.com/typelevel/steward/edit/main/repos.md) file.  This action uses a GitHub token for the Typelevel installation of typelevel-steward and will only work on projects in the Typelevel org.  For external projects, see [diy-steward](https://github.com/armanbilge/diy-steward/).
