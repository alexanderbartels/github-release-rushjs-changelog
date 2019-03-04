# github-release-rushjs-changelog

> Create GitHub releases from `CHANGELOG.md` generated by [rushjs](https://rushjs.io/).

You need:

* a CHANGELOG generated by `rushjs`. 
* a `package.json` with a `version` field. (Updated by rushjs)
* a `package.json` with a `repository` field. The repository to provide the relese information.
* a git tag with the corresponding version in `<pgk.name>_v<pgk.version>` format. (created by `rush publish 
* a `GITHUB_TOKEN` as an env var. See <https://github.com/MoOx/npmpub#requirements> for instructions.

This tool edits the git tag on GitHub and create a GitHub release with the correct `CHANGELOG.md` section.

## Install

```console
npm install github-release-rushjs-changelog
```

## Usage

```console
github-release-rushjs-changelog [--filename CustomChangelog.md]
```

## Advanced Installation and Usage

Add it as a script to your `package.json` so it runs automatically if `rushjs` publishes one of your packages. 


## CONTRIBUTING

* ⇄ Pull requests and ★ Stars are always welcome.
* For bugs and feature requests, please create an issue.

## CHANGELOG

See [CHANGELOG.md](CHANGELOG.md)

## LICENSE

The license is MIT.
See [LICENSE](LICENSE).
