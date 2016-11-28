# kitten-launcher

![Jumping Kitten](http://i.giphy.com/VxbvpfaTTo3le.gif)

`kitten-launcher`'s purpose is to simplify building and integrating
[kitten](https://github.com/KissKissBankBank/kitten) on client applications.

It should eventually have a set of scripts to compile
[kitten](https://github.com/KissKissBankBank/kitten) with
[Webpack](https://webpack.github.io/).

## Installation

As the `kitten-launcher` module is on a
[private registry on Gemfury](https://gemfury.com/help/npm-registry),
you have to setup your npm configuration aka your `.npmrc` to be able to
install all npm dependencies.

Set your default registry in your `.npmrc`:

```sh
npm config set registry https://npm-proxy.fury.io/bob/
```

Set your authentication token in your `.npmrc` by providing your Gemfury
username and password:

```sh
npm login
```

Install the dependency:

```sh
npm install --save kitten-launcher
```

## Release

To release a new version:

- Switch to the `master` branch and pull the last version of it.
- Update the version in `package.json`.
- Update the version in `CHANGELOG.md` and add a new `[unreleased]` section.
- Run this command:

```sh
npm run deploy
```
