# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v7.17.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.17.0) (2022-04-25)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.16.0...v7.17.0)

### Added

- Support Debian 11 [\#241](https://github.com/treydock/puppet-module-keycloak/pull/241) ([vilhelmprytz](https://github.com/vilhelmprytz))

## [v7.16.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.16.0) (2022-04-04)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.15.0...v7.16.0)

### Added

- Support Keycloak 16 [\#239](https://github.com/treydock/puppet-module-keycloak/pull/239) ([treydock](https://github.com/treydock))

## [v7.15.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.15.0) (2022-04-04)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.14.0...v7.15.0)

### Added

- New saml attrs [\#238](https://github.com/treydock/puppet-module-keycloak/pull/238) ([wolfaba](https://github.com/wolfaba))

## [v7.14.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.14.0) (2022-03-14)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.13.0...v7.14.0)

### Added

- add backchannel logout url attribute [\#237](https://github.com/treydock/puppet-module-keycloak/pull/237) ([wolfaba](https://github.com/wolfaba))

## [v7.13.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.13.0) (2022-02-10)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.12.2...v7.13.0)

### Added

- Realm role mapping support [\#233](https://github.com/treydock/puppet-module-keycloak/pull/233) ([mattock](https://github.com/mattock))

## [v7.12.2](https://github.com/treydock/puppet-module-keycloak/tree/v7.12.2) (2022-02-08)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.12.1...v7.12.2)

### Fixed

- Fix authorization services data corruption on unrelated client changes [\#236](https://github.com/treydock/puppet-module-keycloak/pull/236) ([mattock](https://github.com/mattock))

## [v7.12.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.12.1) (2022-01-18)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.12.0...v7.12.1)

### Fixed

- Quota datasource username and password [\#235](https://github.com/treydock/puppet-module-keycloak/pull/235) ([treydock](https://github.com/treydock))
- Fix issues with install\_base /opt/keycloak [\#232](https://github.com/treydock/puppet-module-keycloak/pull/232) ([dmaes](https://github.com/dmaes))

## [v7.12.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.12.0) (2021-11-24)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.11.1...v7.12.0)

### Added

- Add Realm properties and allow custom properties [\#228](https://github.com/treydock/puppet-module-keycloak/pull/228) ([treydock](https://github.com/treydock))

## [v7.11.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.11.1) (2021-11-24)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.11.0...v7.11.1)

### Fixed

- Further fix to set description on keycloak\_flow when not top\_level flow [\#227](https://github.com/treydock/puppet-module-keycloak/pull/227) ([treydock](https://github.com/treydock))
- Fix to set description on keycloak\_flow when not top\_level flow [\#226](https://github.com/treydock/puppet-module-keycloak/pull/226) ([treydock](https://github.com/treydock))

## [v7.11.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.11.0) (2021-11-05)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.10.0...v7.11.0)

### Added

- Replace CentOS 8 support with Rocky 8 [\#221](https://github.com/treydock/puppet-module-keycloak/pull/221) ([treydock](https://github.com/treydock))
- Support stdlib 8.x, mysql 12.x and use puppet/systemd [\#220](https://github.com/treydock/puppet-module-keycloak/pull/220) ([treydock](https://github.com/treydock))
- Add id parameter to keycloak::freeipa\_user\_provider [\#219](https://github.com/treydock/puppet-module-keycloak/pull/219) ([treydock](https://github.com/treydock))

## [v7.10.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.10.0) (2021-09-22)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.9.1...v7.10.0)

### Added

- Add feature `user_managed_access_allowed` property [\#211](https://github.com/treydock/puppet-module-keycloak/pull/211) ([rdcuzins](https://github.com/rdcuzins))

### Fixed

- Fix and tune mangement interface definitions for both master and slave [\#217](https://github.com/treydock/puppet-module-keycloak/pull/217) ([kibahop](https://github.com/kibahop))

## [v7.9.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.9.1) (2021-09-16)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.9.0...v7.9.1)

### Fixed

- set keycloak\_server in keycloak\_conn\_validator from 'localhost' to $service\_bind\_address [\#216](https://github.com/treydock/puppet-module-keycloak/pull/216) ([hugendudel](https://github.com/hugendudel))

## [v7.9.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.9.0) (2021-09-08)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.8.0...v7.9.0)

### Added

- Remove Scientific Linux from metadata.json, still supported [\#213](https://github.com/treydock/puppet-module-keycloak/pull/213) ([treydock](https://github.com/treydock))
- add saml-user-attribute-mapper support [\#212](https://github.com/treydock/puppet-module-keycloak/pull/212) ([aba-rechsteiner](https://github.com/aba-rechsteiner))

### Fixed

- Fix centos/7 in Vagrant failing [\#210](https://github.com/treydock/puppet-module-keycloak/pull/210) ([rdcuzins](https://github.com/rdcuzins))
- Fix invalid module dependency versions [\#209](https://github.com/treydock/puppet-module-keycloak/pull/209) ([rdcuzins](https://github.com/rdcuzins))

## [v7.8.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.8.0) (2021-09-01)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.7.1...v7.8.0)

### Added

- Added support for bearer-only configuration of keycloak\_client [\#207](https://github.com/treydock/puppet-module-keycloak/pull/207) ([verrydtj](https://github.com/verrydtj))

## [v7.7.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.7.1) (2021-08-23)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.7.0...v7.7.1)

### Fixed

- Fix assigning management interfaces to logical interfaces in domain mode [\#206](https://github.com/treydock/puppet-module-keycloak/pull/206) ([kibahop](https://github.com/kibahop))

## [v7.7.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.7.0) (2021-08-16)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.6.0...v7.7.0)

### Added

- Support Keycloak 15.x [\#204](https://github.com/treydock/puppet-module-keycloak/pull/204) ([treydock](https://github.com/treydock))

## [v7.6.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.6.0) (2021-08-13)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.5.1...v7.6.0)

### Added

- Add extra configurations to keycloak realm [\#203](https://github.com/treydock/puppet-module-keycloak/pull/203) ([qboileau](https://github.com/qboileau))

## [v7.5.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.5.1) (2021-08-03)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.5.0...v7.5.1)

### Fixed

- Ensure flow execution will add config if not added on create [\#201](https://github.com/treydock/puppet-module-keycloak/pull/201) ([treydock](https://github.com/treydock))

## [v7.5.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.5.0) (2021-07-12)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.4.1...v7.5.0)

### Added

- Update dependency version ranges [\#200](https://github.com/treydock/puppet-module-keycloak/pull/200) ([treydock](https://github.com/treydock))
- Support Keycloak 14 [\#199](https://github.com/treydock/puppet-module-keycloak/pull/199) ([treydock](https://github.com/treydock))
- Fix Ubuntu acceptance tests [\#198](https://github.com/treydock/puppet-module-keycloak/pull/198) ([treydock](https://github.com/treydock))

## [v7.4.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.4.1) (2021-07-10)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.4.0...v7.4.1)

### Fixed

- Remove prefixes from socket-binding-groups [\#197](https://github.com/treydock/puppet-module-keycloak/pull/197) ([kibahop](https://github.com/kibahop))

## [v7.4.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.4.0) (2021-06-03)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.3.0...v7.4.0)

### Added

- Allow flows and flow executions to depend on SPI deployments [\#196](https://github.com/treydock/puppet-module-keycloak/pull/196) ([treydock](https://github.com/treydock))

## [v7.3.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.3.0) (2021-06-02)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.2.2...v7.3.0)

### Added

- Support Keycloak 13.x [\#195](https://github.com/treydock/puppet-module-keycloak/pull/195) ([treydock](https://github.com/treydock))
- Vagrant: install puppetlabs-postgresql [\#193](https://github.com/treydock/puppet-module-keycloak/pull/193) ([mattock](https://github.com/mattock))

## [v7.2.2](https://github.com/treydock/puppet-module-keycloak/tree/v7.2.2) (2021-04-23)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.2.1...v7.2.2)

### Fixed

- Domain mode sockets [\#192](https://github.com/treydock/puppet-module-keycloak/pull/192) ([kibahop](https://github.com/kibahop))

## [v7.2.1](https://github.com/treydock/puppet-module-keycloak/tree/v7.2.1) (2021-04-17)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.2.0...v7.2.1)

### Fixed

- Fix keycloak\_client to be able to update the secret [\#191](https://github.com/treydock/puppet-module-keycloak/pull/191) ([treydock](https://github.com/treydock))

## [v7.2.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.2.0) (2021-03-26)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.1.0...v7.2.0)

### Added

- Add support for logging to syslog [\#190](https://github.com/treydock/puppet-module-keycloak/pull/190) ([kibahop](https://github.com/kibahop))

## [v7.1.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.1.0) (2021-03-25)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v7.0.0...v7.1.0)

### Added

- FreeIPA/LDAP provider related regression fixes [\#189](https://github.com/treydock/puppet-module-keycloak/pull/189) ([mattock](https://github.com/mattock))

## [v7.0.0](https://github.com/treydock/puppet-module-keycloak/tree/v7.0.0) (2021-03-10)

[Full Changelog](https://github.com/treydock/puppet-module-keycloak/compare/v6.26.0...v7.0.0)

### Changed

- Change default Keycloak version to 12.0.4 [\#188](https://github.com/treydock/puppet-module-keycloak/pull/188) ([treydock](https://github.com/treydock))
- Drop Puppet 5, support Puppet 7 [\#184](https://github.com/treydock/puppet-module-keycloak/pull/184) ([treydock](https://github.com/treydock))

### Added

- Split config.cli templates into smaller files, use epp templates [\#187](https://github.com/treydock/puppet-module-keycloak/pull/187) ([treydock](https://github.com/treydock))
- Support Ubuntu 20.04, bump dependency requirements [\#186](https://github.com/treydock/puppet-module-keycloak/pull/186) ([treydock](https://github.com/treydock))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
