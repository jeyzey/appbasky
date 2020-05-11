# AppBasky Contributor Guide
Welcome to the AppBasky project! We'd love to accept your contributions to this project. Please read the contributors guide below.

Feel free to ask or submit the issue or pull requests. We appreciate any sort of contributions and don't want a wall of rules to get in the way of that.

We want to make contributing to this project as easy and transparent as possible, whethere it's:

* Raising an issue
* Discussing the current state of the code
* Submitting a fix
* Proposing a new features
* Becoming a maintainer

## General
General try to limit the scope of any Pull Request to an atomic update if possible. This way, it's much easier to assess and review your changes.

You should expect a considerably faster turn around if you submit two or more PRs instead of baking them all into one major PR.

## Your First Contribution
We recommend that you work on existing issues before attempting to develop a new feature.

Find an existing issue (e.g. one marked good first issue, or simply ask an owner for suggestions), and respond on the issue thread expressing interest in working on it.

This helps other people know that the issue is active, and hopefully prevents duplicated efforts.

## Pull Request Guidelines
Before you submit a pull request, check that it meets these guidelines:

1. All the pull requests are made against `master` branch.

2. If the pull request adds functionality, the docs should be updated. Put your new functionality into a function with a docstring, and add the feature to the list in README.md

**Docstring** should look like this:
```python
def launch_rocket():
    """
        **Launching Rocket Sequence**

        Locks seatbelts, initiates radio and fires engines.

        :return: Execute Rocket
    """
   # [...]
```
## Coding conventions

- Read and pay attention to current code in the the repository
- For the Python part. we follow pep8 in most cases. We use [flake8][flake8] to check for linting erros. Once you're ready to commit changes, check your code with `flake8`.
- For the Flask part, we follow standard [Flask coding style][flask-coding style].
- And always remember the Zen.

[flake8]: https://flake8.pycqa.org/en/latest/
[flask-coding style]: https://flask.palletsprojects.com/en/1.1.x/styleguide/

## Raising Issues
When raising issues, please specify the following:
* Setup details need to be filled as specified in the issue template clearly for the reviewer to check.
* A scenario where the issue occurred (with details on how to reproduce it).
* Errors and log messages that are displayed by the software.
* Any other details that might be useful.

## Submit Change to Improve Documentation
Getting documentation right is hard! Refer to this [page](https://github.com/AppBasky/appbasky/blob/master/community/CONTRIBUTING-TO-DOC.md) for more information on how you could improve the documentation by submitting pull requests with appropriate tags. Here's a [list of tags](https://github.com/AppBasky/appbasky/blob/master/contribute/LABELS-OF-ISSUES.md) that could be used for the same. Help us keep our documentation clean, easy to understand, and accessible.

## Submit Proposals for New Features
There is always something more that is required, to make it easier to suit your use-cases. Feel free to join the discussion on new features or raise a PR with your proposed change.
* Join our community appbasky.slack.com - Already signed up? Head to our discussions at #appbasky-new-features


## Contributing to Source Code and Bug Fixes
Provide PRs with appropriate tags for bug fixes or enhancements to the source code.

## Solve Existing Issues
Head over to issues to find issues where help is needed from contributors. See our [list of labels guide](https://github.com/AppBasky/appbasky/blob/master/contribute/LABELS-OF-ISSUES.md) to help you find issues that you can solve faster.

A person looking to contribute can take up an issue by claiming it as a comment/assign their GitHub ID to it. In case there is no PR or update in progress for a week on the said issue, then the issue reopens for anyone to take up again. We need to consider high priority issues/regressions where response time must be a day or so.


