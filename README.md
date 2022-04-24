# Copier Template for a Github Action with Automated Semantic Releases

A template for a Github Action using [semantic-release](https://github.com/semantic-release/semantic-release) for
completely automated versioning and releases. It is set up to follow
[Github's best practices for release management](https://docs.github.com/en/actions/creating-actions/about-custom-actions#using-release-management-for-actions)
including creating specific version tags e.g. `v1.0.2` as well as major version tags e.g. `v1` and the latest tag `latest`. It supports
all Github Action types: `composite`, `docker`, and `javascript`, as well as an additional `typescript` type that is already set up to
transpile into a plain `javascript` action.

## Examples

See an example output repository for each of the Github Action types:

- [Composite](https://github.com/nickderobertis/github-actions-semantic-release-composite-example)
- [Docker](https://github.com/nickderobertis/github-actions-semantic-release-docker-example)
- [JavaScript](https://github.com/nickderobertis/github-actions-semantic-release-javascript-example)
- [TypeScript](https://github.com/nickderobertis/github-actions-semantic-release-typescript-example)

## Getting Started

It's recommended to use [Flexlate](https://nickderobertis.github.io/flexlate/) so that you can keep the project updated with changes in the template.

```shell
fxt init-from https://github.com/nickderobertis/copier-github-actions-semantic-release
```

You can also use Copier for the same purpose:

```shell
copier https://github.com/nickderobertis/copier-github-actions-semantic-release.git my-action-repo-name
```

## Developing

This project uses the
[Flexlate Development Tools](https://nickderobertis.github.io/flexlate-dev/).
Get started working on one of the Github action types (`composite`, `docker`, `javascript`, and `typescript`)
with the `serve` command:

```shell
dfxt serve -n javascript
```
