## [1.1.0](https://github.com/slmingol/docker-autoheal/compare/v1.0.2...v1.1.0) (2026-04-10)

### Features

* add GitHub Container Registry (ghcr.io) support ([8b266fb](https://github.com/slmingol/docker-autoheal/commit/8b266fbe8653af7faa16ebb36731bfd05934e5b2))

## [1.0.2](https://github.com/slmingol/docker-autoheal/compare/v1.0.1...v1.0.2) (2026-04-10)

### Bug Fixes

* allow semantic-release to push commits and tags ([ac5dc1a](https://github.com/slmingol/docker-autoheal/commit/ac5dc1a5b55509431c4e09b14bbbc0bee6b2b64c))

## [1.0.1](https://github.com/slmingol/docker-autoheal/compare/v1.0.0...v1.0.1) (2026-04-10)

### Bug Fixes

* improve documentation clarity for version tags ([1d4b335](https://github.com/slmingol/docker-autoheal/commit/1d4b3353270a52c6979e23a8c8077def959dbf2f))

### Documentation

* update README to reflect automated semantic versioning ([9a6cc42](https://github.com/slmingol/docker-autoheal/commit/9a6cc424d9c98a3b29ed185381269d1d9a9d415e))

## 1.0.0 (2026-04-10)

### ⚠ BREAKING CHANGES

* build workflow no longer pushes on main branch, use release workflow instead

### Features

* add automated semantic versioning and conventional commits ([bf6a167](https://github.com/slmingol/docker-autoheal/commit/bf6a1678b4e8ccd0a5c4e90ebb344d202e8fb587))
* add licence ([11daf62](https://github.com/slmingol/docker-autoheal/commit/11daf622171938ad7b0ec11ecf46de44922511fa))

### Bug Fixes

* add in gitignore ([62f7279](https://github.com/slmingol/docker-autoheal/commit/62f7279522f910311c99abf233cb2bd132f0fd52))
* bump alpine version ([07eb586](https://github.com/slmingol/docker-autoheal/commit/07eb586f08aba47e16d773c1115d6bf57e414fcc))
* revert ([bba733b](https://github.com/slmingol/docker-autoheal/commit/bba733b9683649e83436f834b1b66410b6608aef))

### Documentation

* add docker pull stats ([7c9e241](https://github.com/slmingol/docker-autoheal/commit/7c9e241ba892f051d15dfcb35f03caaee94a3b2d))
* add in example on how to map in local timezone ([4b31e38](https://github.com/slmingol/docker-autoheal/commit/4b31e38e75546fac2883c516adaec571a664b4cb))
* add in extra metadata ([d55759e](https://github.com/slmingol/docker-autoheal/commit/d55759e9a026f384c01f25e0ed4acd6edba451c2))
* add in funding yml ([0470754](https://github.com/slmingol/docker-autoheal/commit/0470754f65e9380ab4af7dbb0da24a3e26811f92))
* add in latest, built daily ([c8c73ce](https://github.com/slmingol/docker-autoheal/commit/c8c73ce24c531eb682f0a3e93c44d644526db40b))
* bump version number ([8988af9](https://github.com/slmingol/docker-autoheal/commit/8988af90610c586f07fe8c46364cb3a91ecfb1d2))
* fix typo ([9686a27](https://github.com/slmingol/docker-autoheal/commit/9686a27451cec6caa3b8940996de96589118beec))
* update tagged versions ([4c2d2c9](https://github.com/slmingol/docker-autoheal/commit/4c2d2c9b04f1262cdf9189bd251394a346384ad0))
* version bump ([8798ded](https://github.com/slmingol/docker-autoheal/commit/8798ded18a233a04c1462e41ec666525470fb3ae))

### Continuous Integration

* add missing build script ([5e3779a](https://github.com/slmingol/docker-autoheal/commit/5e3779a5e9c7eec61a49d2eec47143b23632d993))
* alpine 3.11 ([e55bb8c](https://github.com/slmingol/docker-autoheal/commit/e55bb8cecab18bfe41ffc81a91e5184bdecd5e05))
* clean up build script path ([f1db1ed](https://github.com/slmingol/docker-autoheal/commit/f1db1edab6a4f300d888588dc5614d5848285582))
* clean up setup script ([3cc2c43](https://github.com/slmingol/docker-autoheal/commit/3cc2c435561771182cce8b4ad4a1dbfab066f53f))
* fix image name, was deplying to wrong image ([49f98c5](https://github.com/slmingol/docker-autoheal/commit/49f98c56f0d40b9cbcc16d59323f36368b3bc8bd))
* modernize workflow and add testing/security ([4b4b702](https://github.com/slmingol/docker-autoheal/commit/4b4b70289224107a220ee6993b8804a0c0f4fd21))
* move build script to root to allow relative paths to root ([4af2100](https://github.com/slmingol/docker-autoheal/commit/4af2100a2f08a057265b18a2031fadd92661966d))
* Only run on main branch ([ac2750d](https://github.com/slmingol/docker-autoheal/commit/ac2750dfae46f541803518a58254806a087301a4))
* remove unused scripts/config ([ec99645](https://github.com/slmingol/docker-autoheal/commit/ec996452e57224d73d6eabcb5ac01476b6ced235))
* update build to use no external scripts ([77dca12](https://github.com/slmingol/docker-autoheal/commit/77dca128fcc4efe6a48c622205dd82ff9666f1c5))

# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Continuous Integration

- Modernized GitHub Actions workflow
- Added automated testing with shellcheck
- Added Trivy security scanning
- Removed wasteful daily builds
- Added Renovate for dependency updates
- Implemented semantic-release for automated versioning
- Added conventional commit enforcement
