# Changelog

## [0.42.3](https://github.com/saltstack-formulas/openssh-formula/compare/v0.42.2...v0.42.3) (2019-10-27)


### Continuous Integration

* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/5d3f92c))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/88fed56))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/openssh-formula/commit/41d712f))


### Documentation

* **contributing:** remove to use org-level file instead [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/b564d8d))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/8eaf5e4))


### Tests

* **inspec:** fix `config_spec` tests on *BSD (`wheel` not `root`) ([](https://github.com/saltstack-formulas/openssh-formula/commit/047b753))

## [0.42.2](https://github.com/saltstack-formulas/openssh-formula/compare/v0.42.1...v0.42.2) (2019-10-09)


### Bug Fixes

* **config.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/openssh-formula/commit/7e35335))
* **map.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/openssh-formula/commit/55560a6))


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([](https://github.com/saltstack-formulas/openssh-formula/commit/4ca3ca1))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/1b236db))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/32dd705))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([](https://github.com/saltstack-formulas/openssh-formula/commit/4644018))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/openssh-formula/commit/72ade05))

## [0.42.1](https://github.com/saltstack-formulas/openssh-formula/compare/v0.42.0...v0.42.1) (2019-09-16)


### Tests

* **inspec:** add tests based on existing Serverspec tests ([#168](https://github.com/saltstack-formulas/openssh-formula/issues/168)) ([267042c](https://github.com/saltstack-formulas/openssh-formula/commit/267042c)), closes [/travis-ci.org/myii/openssh-formula/jobs/585340845#L1811-L1813](https://github.com//travis-ci.org/myii/openssh-formula/jobs/585340845/issues/L1811-L1813) [/travis-ci.org/myii/openssh-formula/jobs/585356835#L2957-L2965](https://github.com//travis-ci.org/myii/openssh-formula/jobs/585356835/issues/L2957-L2965) [#166](https://github.com/saltstack-formulas/openssh-formula/issues/166)

# [0.42.0](https://github.com/saltstack-formulas/openssh-formula/compare/v0.41.0...v0.42.0) (2019-09-13)


### Features

* **semantic-release:** implement for this formula ([6300ddf](https://github.com/saltstack-formulas/openssh-formula/commit/6300ddf)), closes [#165](https://github.com/saltstack-formulas/openssh-formula/issues/165)
