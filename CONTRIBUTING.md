# Contributing

When contributing to this repository, please first discuss the change you wish
to make via issue, email, or any other method with the owners of this
repository before making a change.

## About the repository configuration

1. This repository is [Commitizen friendly](http://commitizen.github.io/cz-cli/)
    - When you're done with your work and want to commit it just execute
      `git commit`.
    - Thanks to [husky](https://github.com/typicode/husky) some git hooks will
      be executed to automatically: 1. Lint your staged files 2. Execute `prettier` 3. Lint your commit message
    - Commitizen and commitlint are configured to use the
      [Conventional Changelog](https://github.com/conventional-changelog/conventional-changelog)
      pattern
2. [Release Please](https://github.com/googleapis/release-please) is used to
   generate the Changelog and calculate the new version number. This is done
   automatically in a GitHub Action, so there is no need to provide this
   information manually.
