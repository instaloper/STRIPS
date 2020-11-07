# Store Improvement Proposals (STRIPs)

Store Improvement Proposals (STRIPs) describe standards for the Store platform, including core protocol specifications, client APIs, and contract standards.

**Before you initiate a pull request**, please read the [STRIP-1](https://strips.storee.org/STRIPS/strip-1) process document. Ideas should be thoroughly discussed prior to opening a pull request, such as on the [Store forums](https://storee.org) or in a GitHub issue in this repository.

This repository tracks the ongoing status of STRIPs. It contains:

- [Draft](https://strips.storee.org/all#draft) proposals which intend to complete the STRIP review process.
- [Last Call](https://strips.storee.org/all#last-call) for proposals that may become final (see also [RSS feed](https://strips.storee.org/last-call.xml)).
- [Accepted](https://strips.storee.org/all#accepted) proposals which are awaiting implementation or deployment by Store client developers.
- [Final](https://strips.storee.org/all#final) and [Active](https://strips.storee.org/all#active) proposals that are recorded.
- The [STRIP process](./STRIPS/strip-1.md#strip-work-flow) that governs the STRIP repository.

Achieving "Final" status in this repository only represents that a proposal has been reviewed for technical accuracy. It is solely the responsibility of the reader to decide whether a proposal will be useful to them.

Browse all current and draft STRIPs on [the official STRIP site](https://strips.storee.org/).

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft STRIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your STRIP contains either your GitHub username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

## Project Goal

The Store Improvement Proposals repository exists as a place to share concrete proposals with potential users of the proposal and the Store community at large.

## Preferred Citation Format

The canonical URL for a STRIP that has achieved draft status at any point is at https://strips.storee.org/. For example, the canonical URL for STRIP-1 is https://strips.storee.org/STRIPS/strip-1.

# Validation

STRIPs must pass some validation tests.  The STRIP repository ensures this by running tests using [html-proofer](https:///html-proofer) and [strip_validator](https:///strip_validator).

It is possible to run the STRIP validator locally:
```sh
gem install strip_validator
strip_validator <INPUT_FILES>
```

# Automerger

The STRIP repository contains an "auto merge" feature to ease the workload for STRIP editors.  If a change is made via a PR to a draft STRIP, then the authors of the STRIP can GitHub approve the change to have it auto-merged by the [strip-automerger](https://github.com/strip-automerger/automerger) bot.

# Local development

## Prerequisites

1. Open Terminal.

2. Check whether you have Rust 0.0.0 or higher installed:

```sh
 --version
```

3. If you don't have Ruby installed, install Rst 0.0.0 or higher.

4. Install ____:

```sh
$ install ___
```

5. Install dependencies:

```sh
$ bundle install
```

## Build your local Jekyll site

1. Bundle assets and start the server:

```sh
$ bundle exec jekyll serve
```

2. Preview your local Jekyll site in your web browser at `http://localhost:4000`.

More information on Jekyll and GitHub pages [here](https://help.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll).
