## [1.0.100](https://github.com/TriPSs/conventional-changelog-action/compare/v3.1.0...v1.0.100) (2020-12-14)


### Bug Fixes

* Changed yarn --prod to npm ci --prod ([5ba044f](https://github.com/TriPSs/conventional-changelog-action/commit/5ba044f581579411517848e186a425258f30556a))
* Check if repo is shallow before unshallowing ([c5bb2b1](https://github.com/TriPSs/conventional-changelog-action/commit/c5bb2b18afb00739c65c2bee9fc9bb6da52a8c90))
* Empty version files ([091fdfc](https://github.com/TriPSs/conventional-changelog-action/commit/091fdfc6a55a151e3adff5ada382986ead85d58e))
* fail action on push rejection ([206a4e3](https://github.com/TriPSs/conventional-changelog-action/commit/206a4e313a58d868e56629ca59a29a5d8e0105ea))
* Message when using the fallback version ([b525f9a](https://github.com/TriPSs/conventional-changelog-action/commit/b525f9ae66cb03aa2a58cd043963504b911bac31))
* Pull all tags ([3396dfc](https://github.com/TriPSs/conventional-changelog-action/commit/3396dfc4323e48de090308fff522ef4c557f73e5))
* Removed node_modules so rerelease could add them again ([1bac915](https://github.com/TriPSs/conventional-changelog-action/commit/1bac915367fb7a9aef99bf8df172e524b4614909))
* Show info if the version couldn't be detected ([9a324db](https://github.com/TriPSs/conventional-changelog-action/commit/9a324dbd51d0d32c1b9df1a291e14cc20a5bbaff))
* Tag name can also be changed in pre-changelog-generation ([c0f4172](https://github.com/TriPSs/conventional-changelog-action/commit/c0f41727e6b6df5561d358a6bb0aaded9c25da61))
* Test name ([f66f6a2](https://github.com/TriPSs/conventional-changelog-action/commit/f66f6a29a71c9b5ee636cef9ee022f127da37304))
* Use fallback if it's not a valid JSON-File ([97f1bb3](https://github.com/TriPSs/conventional-changelog-action/commit/97f1bb3543e6f2480ef3e699fc695ecb8b3f881b))


### Features

* Add fallback version ([63d0e46](https://github.com/TriPSs/conventional-changelog-action/commit/63d0e46a0b69e3db3f7a5f44e963323afc35d29c))
* Added 'multiple-files' test workflow ([bb40f54](https://github.com/TriPSs/conventional-changelog-action/commit/bb40f54b50fdae3a1a084b597370e7e0f95c28ab))
* Added support for comma-separated version files ([3ba65fd](https://github.com/TriPSs/conventional-changelog-action/commit/3ba65fd7f7bff6e1c60178d49632067c6a8d6bfa))
* Allow to specify a config file ([f0fabf6](https://github.com/TriPSs/conventional-changelog-action/commit/f0fabf6d88a3b7cef366530cc9cad6160a00d128))
* Allow to specify custom tags which override auto generated ones ([8f6aa19](https://github.com/TriPSs/conventional-changelog-action/commit/8f6aa1969f7dd949c0b8c6456c792fa55dd21ce5))



# [3.1.0](https://github.com/TriPSs/conventional-changelog-action/compare/v3.0.0...v3.1.0) (2020-07-13)


### Features

* **pre-commit:** Allow relative path for the pre-commit input ([afea49f](https://github.com/TriPSs/conventional-changelog-action/commit/afea49fa57e678f9c8117d73415a488600b3cd28))
* Add pre-commit script file (hook) ([0aa82ce](https://github.com/TriPSs/conventional-changelog-action/commit/0aa82ce2ad5a23a200c8ce1eeba32eaefc846d9a))



# [3.0.0](https://github.com/TriPSs/conventional-changelog-action/compare/v2.4.0...v3.0.0) (2020-07-03)


### Documentation

* Updated README ([000434c](https://github.com/TriPSs/conventional-changelog-action/commit/000434c4469403159c004a4ed0f5715a06f80448))


### Features

* Added skip commit and skip tag ([3eab241](https://github.com/TriPSs/conventional-changelog-action/commit/3eab2417f9b3e1db3d630b6ec1820106da9a21a9))
* Added support for toml files ([5aff23f](https://github.com/TriPSs/conventional-changelog-action/commit/5aff23f51411f417adf6ea22364d158d335a5fce))
* Added support for yaml files ([bdf8ec0](https://github.com/TriPSs/conventional-changelog-action/commit/bdf8ec04e6f0d493ef859df06ffbeecb1f47a970))
* Added version-file, version-path, skip-version-file options ([d022b0d](https://github.com/TriPSs/conventional-changelog-action/commit/d022b0d7e98b6b13ce0af3e6c44a550256b0ca59))
* Added versioning through GIT ([7143306](https://github.com/TriPSs/conventional-changelog-action/commit/714330612535ae25eb483d0f24fb2fe0c091dc86))
* More git configurations are possible ([9ee9c27](https://github.com/TriPSs/conventional-changelog-action/commit/9ee9c274488b9013bf3dd5e5a1f9af3345901f7e))


### BREAKING CHANGES

* `package-json` is now renamed to `version-file`



# [2.4.0](https://github.com/TriPSs/conventional-changelog-action/compare/v2.3.3...v2.4.0) (2020-06-10)


### Features

* add skip-on-empty feature ([153f866](https://github.com/TriPSs/conventional-changelog-action/commit/153f866251ba4d7c33881dbf082bb1e17974e2a1))



## [2.3.3](https://github.com/TriPSs/conventional-changelog-action/compare/v2.3.2...v2.3.3) (2020-05-08)


### Bug Fixes

* Fixes for CI ([b0698e5](https://github.com/TriPSs/conventional-changelog-action/commit/b0698e5e9b298cc4a6d95889e38638d8d6fd35fa))



