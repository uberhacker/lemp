# Lando LEMP Plugin

The Lando LEMP plugin recipe.

## Installation

```bash
# With npm
npm install @lando/lemp

# With yarn
yarn add @lando/lemp
```

## Issues, Questions and Support

If you have a question or would like some community support we recommend you [join us on Slack](https://launchpass.com/devwithlando). Note that this is the Slack community for [Lando](https://lando.dev) but we are more than happy to help with this module as well!

If you'd like to report a bug or submit a feature request then please [use the issue queue](https://github.com/lando/lemp/issues/new/choose) in this repo.

## Changelog

We try to log all changes big and small in both [THE CHANGELOG](https://github.com/lando/lemp/blob/main/CHANGELOG.md) and the [release notes](https://github.com/lando/lemp/releases).


## Development

* Requires [Node 14+](https://nodejs.org/dist/latest-v14.x/)
* Prefers [Yarn](https://classic.yarnpkg.com/lang/en/docs/install)

```bash
git clone https://github.com/lando/lemp.git && cd lemp
yarn install
```

If you dont' want to install Node 14 or Yarn for whatever reason you can install [Lando](https://docs.lando.dev/basics/installation.html) and use that:

```bash
git clone https://github.com/lando/lemp.git && cd lemp
# Install deps and get node
lando start

# Run commands
lando node
lando yarn
```

## Testing

```bash
# Lint the code
yarn lint

# Run unit tests
yarn test
```

## Releasing

```bash
yarn release
```

## Contributors

<a href="https://github.com/lando/lemp/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=lando/lemp" />
</a>

Made with [contributors-img](https://contrib.rocks).

## Other Resources

* [Important advice](https://www.youtube.com/watch?v=WA4iX5D9Z64)