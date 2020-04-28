# Contributing to AppBasky Documentation

This document describes the process for improving documentation by creating PRs at AppBasky.

Developer documentation is available under the folder: appabasky/contribute

The developer documentation includes anything that will help the community like:

* Design documentation
* Technical Notes
* FAQ
* Process Documentation
* Miscellaneous Notes

We are also looking for people to help us on creating an explainer video or presentation from the community that helps new developers in understanding the AppBasky Project.

At a very high level, the process to contributing and improving the code is pretty simple:

* Submit an issue describing your proposed change
* Create your development branch
* Commit your changes
* Submit your Pull Request

## Submit an issue describing your proposed change

Some general guidelines when submitting issues for developer documentation:

* If the proposed change requires an update to the existing page, please provide a link to the page in the issue.
* If you want to add a new page, then go ahead and open an issue describing the requirement for the new page.

## Create your development branch
* Fork the AppBasky repository and if you have forked it already, rebase with master branch to fetch latest changes to your local system.

* Create a new development branch in your forked repository with the following naming convention: *"task description-#issue"*

**Example**: This change is being developed with the branch named: *AppBasky-Doc-PR-Workflow-#153*

## Commit your changes
* Reference the issue number along with a brief description in your commits
* Set your commit.template to the `COMMIT_TEMPLATE` given in the `.github` directory. `git config --local commit.template $GOPATH/src/github.com/appbasky/appbasky/.github`

## Submit a Pull request
* Rebase your development branch
* Submit the PR from the development branch to the appbasky/appbasky:master
* Incorporate review comments, if any, in the development branch.
* Once the PR is accepted, close the branch.
* After the PR is merged the development branch in the forked repository can be deleted.