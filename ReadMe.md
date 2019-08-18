# Acks.de and Since1988.de - private homepages

Project here to demonstrate inheriting a TYPO3 instance and putting it up to professional level, so maintenance
is easy.

## What I got:

TYPO3 instance version 8.7.24 hosted at jweiland with their standard setup, using the automatic update process.

## The goal:

Professional setup with automated deployment (no change in hosting), but updates and upgrades are done
in a controlled way by the maintainer, not blind by the hosters automatic system.
Instance becomes composer based.
Local setup done with ddev, configuration shipped with the repository.
Frontend testing for local development included, so broken updates are discovered before deployment.

## Usage:

### Installation:

Prerequisites: ddev setup in at least version 10.2 available. For setup see [ddev documentation](https://ddev.readthedocs.io).

1. pull repository
2. `ddev start`
3. `ddev composer install`

### Run Tests:

`ddev exec bin/codecept run`