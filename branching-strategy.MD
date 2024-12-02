# Branching Strategy

## Branches

The repository has the following branches:

- `main` - The main branch for production. This branch should only be updated via pull requests from the `development` branch.
- `development` - The main branch for development. All feature branches should be branched off of this branch.
- `feature/*` - Feature branches for new features.
- `bug/*` - Bug branches for bug fixes.
- `hotfix/*` - Hotfix branches for hotfixes for production.
- `chore/*` - Chore branches for chores (e.g. refactoring, adding tests, etc.)
- `release/*` - Release branches for new versions of the application.
- `docs/*` - Documentation branches for documentation updates.
- `style/*` - Style branches for style updates (e.g. formatting, missing semi-colons, etc.)
- `refactor/*` - Refactor branches for refactoring of the codebase.
- `test/*` - Test branches for adding missing tests.
- `config/*` - Config branches for configuration updates (e.g. updating .gitignore, package.json, etc.)
- `ci/*` - CI branches for CI updates (e.g. updating Travis CI config, GitHub Actions, etc.)
- `perf/*` - Perf branches for performance updates.
- `vendor/*` - Vendor branches for vendor updates (e.g. updating Laravel, Bootstrap, etc.)
- `security/*` - Security branches for security updates.
- `revert/*` - Revert branches for reverting previous commits.
- `merge/*` - Merge branches for merging previous branches.
- `other/*` - Other branches for any other type of update.

## Cloning the Repository

When cloning the repository, you should always clone the `development` branch. This is the branch that all feature branches should be branched off of.

## Branch Naming

Branches are named based on the following convention:

```
{type}/{issue-number}-{description}
```

### Type

The type of branch being created. This can be one of the following:

- `feature` - A new feature
- `bug` - A bug fix
- `hotfix` - A hotfix for production
- `chore` - A chore (e.g. refactoring, adding tests, etc.)
- `release` - A release branch for a new version of the application
- `docs` - A documentation update
- `style` - A style update (e.g. formatting, missing semi-colons, etc.)
- `refactor` - A refactoring of the codebase
- `test` - Adding missing tests
- `config` - A configuration update (e.g. updating .gitignore, package.json, etc.)
- `ci` - A CI update (e.g. updating Travis CI config, GitHub Actions, etc.)
- `perf` - A performance update
- `vendor` - A vendor update (e.g. updating Laravel, Bootstrap, etc.)
- `security` - A security update
- `revert` - A revert of a previous commit
- `merge` - A merge of a previous branch
- `other` - Any other type of update

### Issue Number

The issue number associated with the branch. This is optional, but is recommended for tracking purposes.

### Description

A short description of the branch. This should be in kebab-case.

### Examples

- `feature/1-add-login-page`
- `bug/2-fix-login-page`
- `hotfix/3-fix-production-bug`
- `chore/4-add-tests`
- `release/5-1.0.0`
- `docs/6-update-readme`
- `style/7-fix-formatting`
- `refactor/8-refactor-codebase`
- `test/9-add-tests`
- `config/10-update-gitignore`

## Commit Messages

Commit messages should be formatted as follows:

```
{type}: {description}
```

### Type

The type of commit being made. This can be one of the following:

- `feat` - A new feature
- `fix` - A bug fix
- `hotfix` - A hotfix for production
- `chore` - A chore (e.g. refactoring, adding tests, etc.)
- `release` - A release branch for a new version of the application
- `docs` - A documentation update
- `style` - A style update (e.g. formatting, missing semi-colons, etc.)
- `refactor` - A refactoring of the codebase
- `test` - Adding missing tests
- `config` - A configuration update (e.g. updating .gitignore, package.json, etc.)
- `ci` - A CI update (e.g. updating Travis CI config, GitHub Actions, etc.)
- `perf` - A performance update
- `vendor` - A vendor update (e.g. updating Laravel, Bootstrap, etc.)
- `security` - A security update
- `revert` - A revert of a previous commit
- `merge` - A merge of a previous branch
- `other` - Any other type of update

### Description

A short description of the commit. This should be in kebab-case.

## Pull Requests

Pull requests should be formatted as follows:

```
{type}: {description}
```

### Type

The type of pull request being made. This can be one of the following:

- `feat` - A new feature
- `fix` - A bug fix
- `hotfix` - A hotfix for production
- `chore` - A chore (e.g. refactoring, adding tests, etc.)
- `release` - A release branch for a new version of the application
- `docs` - A documentation update
- `style` - A style update (e.g. formatting, missing semi-colons, etc.)
- `refactor` - A refactoring of the codebase
- `test` - Adding missing tests
- `config` - A configuration update (e.g. updating .gitignore, package.json, etc.)
- `ci` - A CI update (e.g. updating Travis CI config, GitHub Actions, etc.)
- `perf` - A performance update
- `vendor` - A vendor update (e.g. updating Laravel, Bootstrap, etc.)
- `security` - A security update
- `revert` - A revert of a previous commit
- `merge` - A merge of a previous branch
- `other` - Any other type of update

### Description

A short description of the pull request. This should be in kebab-case.

## Releases

Releases should be formatted as follows:

```
{type}: {description}
```

### Type

The type of release being made. This can be one of the following:

- `feat` - A new feature
- `fix` - A bug fix
- `hotfix` - A hotfix for production
- `chore` - A chore (e.g. refactoring, adding tests, etc.)
- `release` - A release branch for a new version of the application
- `docs` - A documentation update
- `style` - A style update (e.g. formatting, missing semi-colons, etc.)
- `refactor` - A refactoring of the codebase
- `test` - Adding missing tests
- `config` - A configuration update (e.g. updating .gitignore, package.json, etc.)
- `ci` - A CI update (e.g. updating Travis CI config, GitHub Actions, etc.)
- `perf` - A performance update
- `vendor` - A vendor update (e.g. updating Laravel, Bootstrap, etc.)
- `security` - A security update
- `revert` - A revert of a previous commit
- `merge` - A merge of a previous branch
- `other` - Any other type of update

### Description

A short description of the release. This should be in kebab-case.
