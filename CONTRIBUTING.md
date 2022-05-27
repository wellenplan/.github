# Contributing Guide

* [New Contributor Guide](#contributing-guide)
  * [Ways to Contribute](#ways-to-contribute)
  * [Find an Issue](#find-an-issue)
  * [Ask for Help](#ask-for-help)
  * [Development Environment Setup](#development-environment-setup)
  * [Pull Request Checklist](#pull-request-checklist)

Welcome! We are glad that you want to contribute to our project! 💖

As you get started, you are in the best position to give us feedback on areas of
our project that we need help with including:

* Problems found during setting up a new development environment
* Gaps in our Quickstart Guide or documentation
* Bugs in our automation scripts

If anything doesn't make sense, or doesn't work when you run it, please open a
bug report and let us know!

## Ways to Contribute

We welcome many different types of contributions including:

* New features
* Builds, CI/CD
* Bug fixes
* Documentation
* Issue Triage
* Answering questions in Discussions
* Web design
* Communications / Social Media / Blog Posts
* Release management

Not everything happens through a GitHub pull request. Please say hi in
[discussions](https://github.com/orgs/wellenplan/discussions) or
[contact us](mailto:hairmare@purplehaze.ch) and let's discuss how we can work
together.

## Find an Issue

We have good first issues for new contributors and help wanted issues suitable
for any contributor. [good first issue](https://github.com/orgs/wellenplan/projects/1/views/2?filterQuery=label%3Agood-first-issue)
has extra information to help you make your first contribution. [help wanted](https://github.com/orgs/wellenplan/projects/1/views/2?filterQuery=label%3Ahelp-wanted)
are issues suitable for someone who isn't a core maintainer and is good to move
onto after your first pull request.

Sometimes there won’t be any issues with these labels. That’s ok! There is
likely still something for you to work on. If you want to contribute but you
don’t know where to start or can't find a suitable issue, you can contact us
via [discussions](https://github.com/orgs/wellenplan/discussions) so we can
find something for you to work on.

Once you see an issue that you'd like to work on, please post a comment saying
that you want to work on it. Something like "I want to work on this" is fine.

## Ask for Help

The best way to reach us with a question when contributing is to ask on

* The original github issue
* [discussions](https://github.com/orgs/wellenplan/discussions)

## Development Environment Setup

We provide information on how to set up a development environment
[here](https://github.com/wellenplan/wellenplan/wiki/Development)
in the Wellenplan Wiki.

## Pull Request Checklist

When you submit your pull request, or you push new commits to it, our automated
systems will run some checks on your new code. We require that your pull request
passes these checks, but we also have more criteria than just that before we can
accept and merge it. We recommend that you check the following things locally
before you submit your code:

* It passes tests: run the following command to run all of the tests locally: `npm test`
* Impacted code has new or updated tests
* Documentation created/updated
* We use GitHub Actions to test all pull requests. We require that all tests succeed on a pull request before it is merged.