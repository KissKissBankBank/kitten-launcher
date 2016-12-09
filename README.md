# kitten-launcher

![Jumping Kitten](http://i.giphy.com/VxbvpfaTTo3le.gif)

`kitten-launcher`'s purpose is to simplify building and integrating
[kitten](https://github.com/KissKissBankBank/kitten) on client applications.

It should eventually have a set of scripts to compile
[kitten](https://github.com/KissKissBankBank/kitten) with
[Webpack](https://webpack.github.io/).

## Installation

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
bin/deploy
```

Then you can publish the module:

```
npm publish
```
