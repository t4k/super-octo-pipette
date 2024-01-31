# super-octo-pipette

## set up an issue form in the [template chooser](https://github.com/t4k/super-octo-pipette/issues/new/choose)

- [Creating issue forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository#creating-issue-forms)
- [`initiate.yml`](.github/ISSUE_TEMPLATE/initiate.yml)

## set up actions that will respond to new issues

- [Workflow permissions](https://github.com/t4k/super-octo-pipette/settings/actions) must be set with **Read and write permissions**
- [`run.yml`](.github/workflows/run.yml)
  - parse the newly created issue and use the data in an external process
