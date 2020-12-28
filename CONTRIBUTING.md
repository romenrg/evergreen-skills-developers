# Contributing to this repository

This page provides information about contributing to this list of Evergreen Skills for Software Developers.

The preferred way of contributing is by means of [Pull Requests](#pull-requests-creation-guidelines) (PRs), but if you cannot afford the time, [issues](https://github.com/romenrg/evergreen-skills-developers/issues) are also welcome, provided you follow the Code of Conduct as mentioned below.

## Code of Conduct

This project and everyone participating in it is governed by the following [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [contact@romenrg.com](mailto:contact@romenrg.com).

## Pull Requests creation guidelines

### First, get your copy

* Fork the repository on GitHub.
* Clone the forked repository to your machine.
* Set up the official repository as a new "remote" in your cloned repository so that you can fetch new changes from it.

For more information, please refer to [GitHub's instructions on this](https://help.github.com/articles/fork-a-repo/).

### Then, propose Changes

To submit changes:
 * Make sure your local copy is updated.
 * From your updated master branch, create a new dedicated branch locally (`git checkout -b <name-of-new-branch>`).
 * Add your changes by creating [_micro commits_](https://lucasr.org/2011/01/29/micro-commits/).
 * Once your changes are completed, push them to your fork.
 * Finally, create a [GitHub Pull Request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) from your fork, by using GitHub's web interface.

When your PR is submitted, some checks will automatically be run as part of a CI process running in CodeShip. Please, pay attention to the result of this process, so that you can fix any errors that are detected and leave the PR in a stable status for maintainers to review.

When your Pull Request is ready to be merged, the repository maintainers will integrate it and it will be published in the next release.
