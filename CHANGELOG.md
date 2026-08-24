## [2.0.3](https://github.com/AllanLny/Lorexia/compare/v2.0.2...v2.0.3) (2026-08-17)


### Bug Fixes

* fixed auto release on new tag ([3c0e5c2](https://github.com/AllanLny/Lorexia/commit/3c0e5c25a819c2f832331dde06804d73a50a7196))
* fixed auto release on new tag ([93d2e59](https://github.com/AllanLny/Lorexia/commit/93d2e59a591022817a85150fb3331603d123f2ef))

## [2.0.2](https://github.com/AllanLny/Lorexia/compare/v2.0.1...v2.0.2) (2026-08-17)


### Bug Fixes

* add auto 5e sync ([46371b2](https://github.com/AllanLny/Lorexia/commit/46371b2fea383a8faca08bed23a1cfb8c1d26438))
* update autoupdate ([4236f9e](https://github.com/AllanLny/Lorexia/commit/4236f9e2308f519a9489213312dc05de46fc2bb4))
* update autoupdate ([51c6e98](https://github.com/AllanLny/Lorexia/commit/51c6e9825d9d1dd19cf11383d45dd81f53138242))

# [1.16.0](https://github.com/AllanLny/Lorexia/compare/v1.15.7...v1.16.0) (2026-08-16)


### Bug Fixes

* e2e test fixed ([ecd61e5](https://github.com/AllanLny/Lorexia/commit/ecd61e58acf1e3605286ac86652f31b57e06b6af))
* improvement ([7ad0b0d](https://github.com/AllanLny/Lorexia/commit/7ad0b0d7eaf4ecd4ec66e864615a26eca9d91a50))
* improvement ([1957d8e](https://github.com/AllanLny/Lorexia/commit/1957d8e17af70f698f608a75aa641a259caf96b1))
* test e2e cicd ([ce2d18a](https://github.com/AllanLny/Lorexia/commit/ce2d18a009308e77cbc3e84ac54875248f6ea6ff))


### Features

* add setting pages + preference ([d1e19b2](https://github.com/AllanLny/Lorexia/commit/d1e19b2433b1816428ff632e776f6f7ec640be20))
* add test ([6e3f516](https://github.com/AllanLny/Lorexia/commit/6e3f516e03639e7acd132866ed45c525f4094703))

## [1.15.7](https://github.com/AllanLny/Lorexia/compare/v1.15.6...v1.15.7) (2026-08-09)


### Bug Fixes

* **equipment:** add missing CSS for layout + gap between Inventaire/Monnaie ([8a9134d](https://github.com/AllanLny/Lorexia/commit/8a9134d3272074e0348573d4dbbc3c9aecd76454))

## [1.15.6](https://github.com/AllanLny/Lorexia/compare/v1.15.5...v1.15.6) (2026-08-09)


### Bug Fixes

* **release:** refresh apt index before installing Linux deps; use libfuse2t64 ([d5c4d91](https://github.com/AllanLny/Lorexia/commit/d5c4d91961bedb53699f84983413fc25c0bd0dc2))

## [1.15.5](https://github.com/AllanLny/Lorexia/compare/v1.15.4...v1.15.5) (2026-08-09)


### Bug Fixes

* remove orphaned code causing SyntaxError in bug report handler ([63e7c0d](https://github.com/AllanLny/Lorexia/commit/63e7c0d4e2330eade3421d83be35a07d5c92c838))

## [1.15.4](https://github.com/AllanLny/Lorexia/compare/v1.15.3...v1.15.4) (2026-08-09)


### Bug Fixes

* remove .env loading entirely from Electron client — hardcoded bugReporter config ([c615c1f](https://github.com/AllanLny/Lorexia/commit/c615c1fbaad3701c4dc25f88637bc5ec4804062d))

## [1.15.3](https://github.com/AllanLny/Lorexia/compare/v1.15.2...v1.15.3) (2026-08-09)


### Bug Fixes

* improve bug report error handling + debug logging ([7f14221](https://github.com/AllanLny/Lorexia/commit/7f142217fb3be9d48fa02dd84a1840f89c5b5add))

## [1.15.2](https://github.com/AllanLny/Lorexia/compare/v1.15.1...v1.15.2) (2026-08-09)


### Bug Fixes

* only load .env in dev mode so production uses hardcoded bugReporter URL ([77bc518](https://github.com/AllanLny/Lorexia/commit/77bc51893053051b5521a890cf8902f7b2e3a4b9))
* show update errors to user + handle downloadUpdate rejection on Windows ([95fa3e3](https://github.com/AllanLny/Lorexia/commit/95fa3e3422d0bd41fc68b8f6316c1b9431ddefc7))
* sync package-lock.json (semantic-release lockfile drift) ([a21e8ba](https://github.com/AllanLny/Lorexia/commit/a21e8ba885d771ead9bffb0015f747f2399cd752))

## [1.15.1](https://github.com/AllanLny/Lorexia/compare/v1.15.0...v1.15.1) (2026-08-09)


### Bug Fixes

* add dotenv to server package.json for bugReporter ([61141f8](https://github.com/AllanLny/Lorexia/commit/61141f81818d3eaec68963b211bcf858d42df76c))

# [1.15.0](https://github.com/AllanLny/Lorexia/compare/v1.14.0...v1.15.0) (2026-08-09)


### Bug Fixes

* add all files ([8b1b0d8](https://github.com/AllanLny/Lorexia/commit/8b1b0d8bbbfeb1b71b9ada828d49ee17ce1d8678))
* e2e passed ([2a4590d](https://github.com/AllanLny/Lorexia/commit/2a4590de29157ef7c7f45253278ba0d871722d3c))


### Features

* bug report server + Render deployment + proxy fix ([d5fb039](https://github.com/AllanLny/Lorexia/commit/d5fb039c09f657d4a08967747db4dc9502129f8e))

# [1.14.0](https://github.com/AllanLny/Lorexia/compare/v1.13.1...v1.14.0) (2026-07-07)


### Features

* precommit diff checker + css modal classe guide ([5bd0b05](https://github.com/AllanLny/Lorexia/commit/5bd0b054b8a484f085a6f34cb7d166c010be5bab))

## [1.13.1](https://github.com/AllanLny/Lorexia/compare/v1.13.0...v1.13.1) (2026-07-06)


### Bug Fixes

* sqlite version ([e493b0b](https://github.com/AllanLny/Lorexia/commit/e493b0b4e534e6bd365e07e958377c7a3c3dc887))

## [1.11.4](https://github.com/AllanLny/Lorexia/compare/v1.11.3...v1.11.4) (2026-05-17)


### Bug Fixes

* all e2e pased now ([ac14576](https://github.com/AllanLny/Lorexia/commit/ac14576f92a3c73742d5d1289d2b410ef6b4cc51))

## [1.11.3](https://github.com/AllanLny/Lorexia/compare/v1.11.2...v1.11.3) (2026-05-09)


### Bug Fixes

* ia know upgrade entities desc, and don't add knew entité to keep it accurate ([bc906cb](https://github.com/AllanLny/Lorexia/commit/bc906cb98a3b678b458fbbc1ea80c9738180d6e5))
* ia know upgrade entities desc, and don't add knew entité to keep it accurate ([6c27a10](https://github.com/AllanLny/Lorexia/commit/6c27a107bda11307af8a79ee9580b9ed001cbfd2))
* improve analyse system ([3373f6c](https://github.com/AllanLny/Lorexia/commit/3373f6cf40e72953e24a4a7e55d23f84d045905f))

## [1.11.2](https://github.com/AllanLny/Lorexia/compare/v1.11.1...v1.11.2) (2026-05-08)


### Bug Fixes

* delete the manual extraction btn bcause it's useless ([96c75b0](https://github.com/AllanLny/Lorexia/commit/96c75b0235e32126741d8ee83d80be06384a0630))

## [1.11.1](https://github.com/AllanLny/Lorexia/compare/v1.11.0...v1.11.1) (2026-05-08)


### Bug Fixes

* fix some things ([69d6bb5](https://github.com/AllanLny/Lorexia/commit/69d6bb51d5fdcbbb5b417f3ebfff38764d4494ba))

# [1.11.0](https://github.com/AllanLny/Lorexia/compare/v1.10.7...v1.11.0) (2026-05-05)


### Features

* add fullscreen mode ([ebe3fdd](https://github.com/AllanLny/Lorexia/commit/ebe3fdd35f6ee72400dfb62f278720e646e9bf1b))

## [1.10.7](https://github.com/AllanLny/Lorexia/compare/v1.10.6...v1.10.7) (2026-05-03)


### Bug Fixes

* fix auto maj feature ([049e65a](https://github.com/AllanLny/Lorexia/commit/049e65a186a1451d9a73fa5617a87bfaba1a019d))

## [1.10.6](https://github.com/AllanLny/Lorexia/compare/v1.10.5...v1.10.6) (2026-05-03)


### Bug Fixes

* manual release ([c130030](https://github.com/AllanLny/Lorexia/commit/c1300304b3dcac27ba6e2e9f33b1c6f690b2f2cf))

## [1.10.5](https://github.com/AllanLny/Lorexia/compare/v1.10.4...v1.10.5) (2026-05-02)


### Bug Fixes

* release is now on this repo and on the public one ([801515e](https://github.com/AllanLny/Lorexia/commit/801515ee634f65ae26d327f94ae880eb4c538359))

## [1.10.4](https://github.com/AllanLny/Lorexia/compare/v1.10.3...v1.10.4) (2026-05-02)


### Bug Fixes

* fis e2e test ([#3](https://github.com/AllanLny/Lorexia/issues/3)) ([8680f83](https://github.com/AllanLny/Lorexia/commit/8680f83777abf200b8921683dd786c0a1a8fddb1))

## [1.10.3](https://github.com/AllanLny/Lorexia/compare/v1.10.2...v1.10.3) (2026-05-01)


### Bug Fixes

* fix workflow ([508cd25](https://github.com/AllanLny/Lorexia/commit/508cd2546c8effe316393f84fc78942bacbef06c))

## [1.10.2](https://github.com/AllanLny/Lorexia/compare/v1.10.1...v1.10.2) (2026-04-27)


### Bug Fixes

* fix btn on introduction modal ([1577f0e](https://github.com/AllanLny/Lorexia/commit/1577f0eaa3bab074661f3a6935810e4cd887c051))

## [1.10.1](https://github.com/AllanLny/Lorexia/compare/v1.10.0...v1.10.1) (2026-04-27)


### Bug Fixes

* fix ai check to exclude some files ([7c45546](https://github.com/AllanLny/Lorexia/commit/7c455464afd6c0a6c0d77f5876cccadcf3a98aa7))
* fix all test failed ([ce055dc](https://github.com/AllanLny/Lorexia/commit/ce055dcaf5b4115e3485f41137b3d14582d9074a))

# [1.10.0](https://github.com/AllanLny/Lorexia/compare/v1.9.5...v1.10.0) (2026-04-27)


### Features

* add multi class possibility ([a8e9782](https://github.com/AllanLny/Lorexia/commit/a8e978235560e39d92be20a554519858ad89be1c))

## [1.9.5](https://github.com/AllanLny/Lorexia/compare/v1.9.4...v1.9.5) (2026-04-26)


### Bug Fixes

* uniform cicd ([709676c](https://github.com/AllanLny/Lorexia/commit/709676cade465abe811743f8bc1f48fd14cb0f07))

## [1.9.4](https://github.com/AllanLny/Lorexia/compare/v1.9.3...v1.9.4) (2026-04-26)


### Bug Fixes

* cleanup get all artifact ([70a94e4](https://github.com/AllanLny/Lorexia/commit/70a94e465b37273811531ad72b20f9f3ae9235c1))

## [1.9.3](https://github.com/AllanLny/Lorexia/compare/v1.9.2...v1.9.3) (2026-04-25)


### Bug Fixes

* keep 3 last release, and 1 by each type ([d1660c3](https://github.com/AllanLny/Lorexia/commit/d1660c30bbc7786cbaaf20a4b173544d7c5909c1))

## [1.9.2](https://github.com/AllanLny/Lorexia/compare/v1.9.1...v1.9.2) (2026-04-25)


### Bug Fixes

* fix issue on all cicd ([b103159](https://github.com/AllanLny/Lorexia/commit/b10315961f96303799f6186f278913343fa81832))

## [1.9.1](https://github.com/AllanLny/Lorexia/compare/v1.9.0...v1.9.1) (2026-04-25)


### Bug Fixes

* fix issue on all cicd ([e5a3e7b](https://github.com/AllanLny/Lorexia/commit/e5a3e7bee26c5de6cca71c10342c6d9276cb628c))

# [1.9.0](https://github.com/AllanLny/Lorexia/compare/v1.8.0...v1.9.0) (2026-04-25)


### Features

* add cleanup artifact workflow ([199c44d](https://github.com/AllanLny/Lorexia/commit/199c44de30235608a0c536a3cfb5d66b91c38783))

# [1.8.0](https://github.com/AllanLny/Lorexia/compare/v1.7.0...v1.8.0) (2026-04-19)


### Features

* add workflow dispath ([6bccbd4](https://github.com/AllanLny/Lorexia/commit/6bccbd4608f2e76394ecf2209a1c5ba918eb5c87))

# [1.7.0](https://github.com/AllanLny/Lorexia/compare/v1.6.0...v1.7.0) (2026-04-19)


### Bug Fixes

* update GITHUB on GH ([7f98218](https://github.com/AllanLny/Lorexia/commit/7f98218e9de096c2ee8b2f01d2d61440c7288398))


### Features

* feat new modal edit when parchemin close ([519abfe](https://github.com/AllanLny/Lorexia/commit/519abfe14b9025e2db0d00fbcf0e955c74630736))

# [1.6.0](https://github.com/AllanLny/Lorexia/compare/v1.5.0...v1.6.0) (2026-04-19)


### Bug Fixes

* resolve all TypeScript CI errors (TS6133, TS2339, TS7006, TS2345, TS2551, TS2741) ([f33b597](https://github.com/AllanLny/Lorexia/commit/f33b59715757ef0e2b08cdced97c96d2f294a89f))


### Features

* add 5eTOOLS DATA instead of api ([949154e](https://github.com/AllanLny/Lorexia/commit/949154ed3c3d06889dc0cb754dcfa0c04b270b74))
* add character player card with all class/race ([c524abd](https://github.com/AllanLny/Lorexia/commit/c524abd181c910cbfa1539ac85e87066407eb61a))

# [1.5.0](https://github.com/AllanLny/Lorexia/compare/v1.4.0...v1.5.0) (2026-03-08)


### Features

* fix cicd yaml error ([66b1286](https://github.com/AllanLny/Lorexia/commit/66b12860a4b4a0e42bc3dd7f46667744b5d5a90b))
* improve release cicd ([ee7c204](https://github.com/AllanLny/Lorexia/commit/ee7c2040aa6a574ab5ddcff37cb49ededcbdea83))

# [1.4.1](https://github.com/AllanLny/Lorexia/compare/v1.4.0...v1.4.1) (2026-03-08)


### Features

* improve release cicd ([2766d93](https://github.com/AllanLny/Lorexia/commit/2766d934dd24d1ea85628f53e81f9fee2f28548d))
* improve release cicd ([9e74dbc](https://github.com/AllanLny/Lorexia/commit/9e74dbc753fe19097940c26b63ac03dc5256bb93))
* improve release cicd ([665eed8](https://github.com/AllanLny/Lorexia/commit/665eed8c346a9948a0ae0a6803a5e2ce8e29c4a3))
* improve release cicd ([69c6b6a](https://github.com/AllanLny/Lorexia/commit/69c6b6aa9cfb34f2701c55c0530493005573a896))
* now artifact gh have an retention days set to 5days ([7401039](https://github.com/AllanLny/Lorexia/commit/740103944b5e7fe1f6fbb032ab378159f6c46485))

# [1.4.0](https://github.com/AllanLny/Lorexia/compare/v1.3.0...v1.4.0) (2026-03-08)


### Features

* now artifact gh have an retention days set to 5days ([7401039](https://github.com/AllanLny/Lorexia/commit/740103944b5e7fe1f6fbb032ab378159f6c46485))

# [1.3.0](https://github.com/AllanLny/Lorexia/compare/v1.2.1...v1.3.0) (2026-03-04)


### Bug Fixes

* delete top border on modal footer delete, improve ia prompt ([3a4a326](https://github.com/AllanLny/Lorexia/commit/3a4a3262e17bf0e7e53e20e52b5e4ef28af9f27d))


### Features

* some test ([606acfb](https://github.com/AllanLny/Lorexia/commit/606acfbe596cc5014585983f2bbcdc0c9987e07c))

## [1.2.1](https://github.com/AllanLny/Lorexia/compare/v1.2.0...v1.2.1) (2026-03-02)


### Bug Fixes

* improve script rpm to catch the good deb version ([5053bf1](https://github.com/AllanLny/Lorexia/commit/5053bf1e33c31b525ed11d94caede692362baeab))

# [1.2.0](https://github.com/AllanLny/Lorexia/compare/v1.1.0...v1.2.0) (2026-03-02)


### Features

* add auto bumb release on code with semantic release ([2259b89](https://github.com/AllanLny/Lorexia/commit/2259b899dcc8585a31fd0d19ebdd14d8efa08ad8))
* add import export btn, improve explorateur, and settings modal ([6d8a69c](https://github.com/AllanLny/Lorexia/commit/6d8a69c9722c572fa9d7035a14e9146f27e91b1b))
* add import export btn, improve explorateur, and settings modal ([435e80a](https://github.com/AllanLny/Lorexia/commit/435e80a0e8438b40132ecb5373ba3b79e4526afe))

# [1.1.0](https://github.com/AllanLny/Lorexia/compare/v1.0.1...v1.1.0) (2026-03-01)


### Bug Fixes

* issue when add '/' command now we can write long words ([fd32d2e](https://github.com/AllanLny/Lorexia/commit/fd32d2e935116663958f16ab92a6494bed612e12))
* release image name match with tag/release version ([f0ba3b4](https://github.com/AllanLny/Lorexia/commit/f0ba3b40905bc0a8377d0300d315f05311552d72))


### Features

* add rpm release + some script + vscode improve ([7dcfcc5](https://github.com/AllanLny/Lorexia/commit/7dcfcc58fe22d8476616d8a85a4b6bac683d15b1))

## [1.0.1](https://github.com/AllanLny/Lorexia/compare/v1.0.0...v1.0.1) (2026-02-28)


### Bug Fixes

* lighthousse + test e2e ([5714498](https://github.com/AllanLny/Lorexia/commit/5714498077731871385630d1ada7037de5f357b8))

# 1.0.0 (2026-02-27)


### Bug Fixes

* add margin tob on tab nav ([3185648](https://github.com/AllanLny/Lorexia/commit/318564813d497c861d66cf10b8864be5842895cb))
* add scrool with keyboard for the autocompletion modal ([f3f249d](https://github.com/AllanLny/Lorexia/commit/f3f249d2c2c55841b7df17f03c5883b5e1fd7060))
* autocompletion improve ([ab95df1](https://github.com/AllanLny/Lorexia/commit/ab95df1c63635eabde70896822175c3ca9ac6ebb))
* change JDR Brain name to Lorexia ([d105b2f](https://github.com/AllanLny/Lorexia/commit/d105b2f054abedd2ad66b3c56adb402e137872cd))
* chat section to match with the app and improve UI/UX ([0cb41db](https://github.com/AllanLny/Lorexia/commit/0cb41db988f85d9116fc735f2e8e334c7ae33d7b))
* exclude flatpak builder on json ([05aaaa1](https://github.com/AllanLny/Lorexia/commit/05aaaa146192ee26db841d4ee1fbf538a6fe9299))
* fix e2e cicd test ([f7d7bd5](https://github.com/AllanLny/Lorexia/commit/f7d7bd5d2cb28c98cdb58c021fffa9d61548a92c))
* fix e2e test ([e1bf71c](https://github.com/AllanLny/Lorexia/commit/e1bf71c1237390d30501daf21c865e65d8dd2a62))
* fix issues ([4051e8c](https://github.com/AllanLny/Lorexia/commit/4051e8c2daa198a9318d7b5e00acba6bd1ad78c0))
* lighthousse to use preset perf and not mobile preset ([1d9e69d](https://github.com/AllanLny/Lorexia/commit/1d9e69d7762a65e8bbd56c7823a0cb8db0ad9f33))
* logo and nav bar gap ([ec8c38f](https://github.com/AllanLny/Lorexia/commit/ec8c38ff4ab7f2e0cbdf28dd6bf31e8aa797d668))
* nouvelle sessions btn ui fix ([9aeec42](https://github.com/AllanLny/Lorexia/commit/9aeec4247ccd793a1ec71d07299eb5c99849db7a))
* package json ([6eb6b1b](https://github.com/AllanLny/Lorexia/commit/6eb6b1b37707c9c93e1dbd384a7452a2553555f5))
* ui btn fix on note feature ([6bce1e8](https://github.com/AllanLny/Lorexia/commit/6bce1e8d7b80cf9b0e9bb5c5e45b7f9bb0a12340))
* ui to uses reusable component, and some fix ([5ebe2cd](https://github.com/AllanLny/Lorexia/commit/5ebe2cd68219c64466bfd8f28becceea0c4b9cbd))
* update all ci ([4d57008](https://github.com/AllanLny/Lorexia/commit/4d57008322349353d93dda6dd147d9e6f46dc550))
* update package-lock ([a1038b0](https://github.com/AllanLny/Lorexia/commit/a1038b0ece4f55094ccc10ea4e0550959ace5de3))
* update package-lock ([347af50](https://github.com/AllanLny/Lorexia/commit/347af50342784d17b98d9a95405f57ed97cad55a))
* update package-lock and add format-json script ([783a663](https://github.com/AllanLny/Lorexia/commit/783a66316860604281281488806ed35d29169c7e))


### Features

*  improve ui ([36a195b](https://github.com/AllanLny/Lorexia/commit/36a195b24e599ac7359d67aa62c05b7098d175b2))
* add autocompletion ([b578af5](https://github.com/AllanLny/Lorexia/commit/b578af5140461ece30439b8b38c218f1459f2cb2))
* add Hook to factory code ([62eda99](https://github.com/AllanLny/Lorexia/commit/62eda99d682b17f4672d8c1b92c5d064c26e0729))
* add ia verifier + improve ui ([0ab40a2](https://github.com/AllanLny/Lorexia/commit/0ab40a2b329394a5c98c0112cc7c4dee34e0ecdb))
* add logo ([f25a4f4](https://github.com/AllanLny/Lorexia/commit/f25a4f4421c8a537e822c5d98cff3a8f46358870))
* **datalogical:** improve app + improve data extraction logical ([fc0f35e](https://github.com/AllanLny/Lorexia/commit/fc0f35edb8eea1fc1523d1b7dd3e8d248de374bf))
* improve gitignore ([25963ec](https://github.com/AllanLny/Lorexia/commit/25963ec30e4ab35cbf8141a38969bfd1a910f91b))
* improve gitignore + add release possibility ([09b9918](https://github.com/AllanLny/Lorexia/commit/09b991858aac61606a99677abe16f50afd94bba5))
* improve ia setting modal ([facd0a5](https://github.com/AllanLny/Lorexia/commit/facd0a52580216a36001926ac07d3828c95ca5c4))
* qol upgrade ([8cf7f13](https://github.com/AllanLny/Lorexia/commit/8cf7f1371234c0e83c55ebbebfe729ea7ac8aab2))
* save pj now ([3b6f4da](https://github.com/AllanLny/Lorexia/commit/3b6f4da8576f388e77adb004e1a7e2831064993a))
* **ui:** implement automatic Ollama installer with React Portal modals ([e1d55f4](https://github.com/AllanLny/Lorexia/commit/e1d55f4c7e16fc141d8bdf93d6ded17a5133b19c))


### BREAKING CHANGES

* **ui:** Modal rendering now uses React Portal, requires #modal-root element

# 1.0.0 (2026-02-27)


### Bug Fixes

* add margin tob on tab nav ([3185648](https://github.com/AllanLny/Lorexia/commit/318564813d497c861d66cf10b8864be5842895cb))
* add scrool with keyboard for the autocompletion modal ([f3f249d](https://github.com/AllanLny/Lorexia/commit/f3f249d2c2c55841b7df17f03c5883b5e1fd7060))
* autocompletion improve ([ab95df1](https://github.com/AllanLny/Lorexia/commit/ab95df1c63635eabde70896822175c3ca9ac6ebb))
* change JDR Brain name to Lorexia ([d105b2f](https://github.com/AllanLny/Lorexia/commit/d105b2f054abedd2ad66b3c56adb402e137872cd))
* chat section to match with the app and improve UI/UX ([0cb41db](https://github.com/AllanLny/Lorexia/commit/0cb41db988f85d9116fc735f2e8e334c7ae33d7b))
* exclude flatpak builder on json ([05aaaa1](https://github.com/AllanLny/Lorexia/commit/05aaaa146192ee26db841d4ee1fbf538a6fe9299))
* fix e2e test ([e1bf71c](https://github.com/AllanLny/Lorexia/commit/e1bf71c1237390d30501daf21c865e65d8dd2a62))
* fix issues ([4051e8c](https://github.com/AllanLny/Lorexia/commit/4051e8c2daa198a9318d7b5e00acba6bd1ad78c0))
* logo and nav bar gap ([ec8c38f](https://github.com/AllanLny/Lorexia/commit/ec8c38ff4ab7f2e0cbdf28dd6bf31e8aa797d668))
* nouvelle sessions btn ui fix ([9aeec42](https://github.com/AllanLny/Lorexia/commit/9aeec4247ccd793a1ec71d07299eb5c99849db7a))
* package json ([6eb6b1b](https://github.com/AllanLny/Lorexia/commit/6eb6b1b37707c9c93e1dbd384a7452a2553555f5))
* ui btn fix on note feature ([6bce1e8](https://github.com/AllanLny/Lorexia/commit/6bce1e8d7b80cf9b0e9bb5c5e45b7f9bb0a12340))
* ui to uses reusable component, and some fix ([5ebe2cd](https://github.com/AllanLny/Lorexia/commit/5ebe2cd68219c64466bfd8f28becceea0c4b9cbd))
* update all ci ([4d57008](https://github.com/AllanLny/Lorexia/commit/4d57008322349353d93dda6dd147d9e6f46dc550))
* update package-lock ([a1038b0](https://github.com/AllanLny/Lorexia/commit/a1038b0ece4f55094ccc10ea4e0550959ace5de3))
* update package-lock ([347af50](https://github.com/AllanLny/Lorexia/commit/347af50342784d17b98d9a95405f57ed97cad55a))
* update package-lock and add format-json script ([783a663](https://github.com/AllanLny/Lorexia/commit/783a66316860604281281488806ed35d29169c7e))


### Features

*  improve ui ([36a195b](https://github.com/AllanLny/Lorexia/commit/36a195b24e599ac7359d67aa62c05b7098d175b2))
* add autocompletion ([b578af5](https://github.com/AllanLny/Lorexia/commit/b578af5140461ece30439b8b38c218f1459f2cb2))
* add Hook to factory code ([62eda99](https://github.com/AllanLny/Lorexia/commit/62eda99d682b17f4672d8c1b92c5d064c26e0729))
* add ia verifier + improve ui ([0ab40a2](https://github.com/AllanLny/Lorexia/commit/0ab40a2b329394a5c98c0112cc7c4dee34e0ecdb))
* add logo ([f25a4f4](https://github.com/AllanLny/Lorexia/commit/f25a4f4421c8a537e822c5d98cff3a8f46358870))
* **datalogical:** improve app + improve data extraction logical ([fc0f35e](https://github.com/AllanLny/Lorexia/commit/fc0f35edb8eea1fc1523d1b7dd3e8d248de374bf))
* improve gitignore ([25963ec](https://github.com/AllanLny/Lorexia/commit/25963ec30e4ab35cbf8141a38969bfd1a910f91b))
* improve gitignore + add release possibility ([09b9918](https://github.com/AllanLny/Lorexia/commit/09b991858aac61606a99677abe16f50afd94bba5))
* improve ia setting modal ([facd0a5](https://github.com/AllanLny/Lorexia/commit/facd0a52580216a36001926ac07d3828c95ca5c4))
* qol upgrade ([8cf7f13](https://github.com/AllanLny/Lorexia/commit/8cf7f1371234c0e83c55ebbebfe729ea7ac8aab2))
* save pj now ([3b6f4da](https://github.com/AllanLny/Lorexia/commit/3b6f4da8576f388e77adb004e1a7e2831064993a))
* **ui:** implement automatic Ollama installer with React Portal modals ([e1d55f4](https://github.com/AllanLny/Lorexia/commit/e1d55f4c7e16fc141d8bdf93d6ded17a5133b19c))


### BREAKING CHANGES

* **ui:** Modal rendering now uses React Portal, requires #modal-root element

# 1.0.0 (2026-02-27)


### Bug Fixes

* add margin tob on tab nav ([3185648](https://github.com/AllanLny/Lorexia/commit/318564813d497c861d66cf10b8864be5842895cb))
* add scrool with keyboard for the autocompletion modal ([f3f249d](https://github.com/AllanLny/Lorexia/commit/f3f249d2c2c55841b7df17f03c5883b5e1fd7060))
* autocompletion improve ([ab95df1](https://github.com/AllanLny/Lorexia/commit/ab95df1c63635eabde70896822175c3ca9ac6ebb))
* change JDR Brain name to Lorexia ([d105b2f](https://github.com/AllanLny/Lorexia/commit/d105b2f054abedd2ad66b3c56adb402e137872cd))
* chat section to match with the app and improve UI/UX ([0cb41db](https://github.com/AllanLny/Lorexia/commit/0cb41db988f85d9116fc735f2e8e334c7ae33d7b))
* exclude flatpak builder on json ([05aaaa1](https://github.com/AllanLny/Lorexia/commit/05aaaa146192ee26db841d4ee1fbf538a6fe9299))
* fix e2e test ([e1bf71c](https://github.com/AllanLny/Lorexia/commit/e1bf71c1237390d30501daf21c865e65d8dd2a62))
* fix issues ([4051e8c](https://github.com/AllanLny/Lorexia/commit/4051e8c2daa198a9318d7b5e00acba6bd1ad78c0))
* logo and nav bar gap ([ec8c38f](https://github.com/AllanLny/Lorexia/commit/ec8c38ff4ab7f2e0cbdf28dd6bf31e8aa797d668))
* nouvelle sessions btn ui fix ([9aeec42](https://github.com/AllanLny/Lorexia/commit/9aeec4247ccd793a1ec71d07299eb5c99849db7a))
* package json ([6eb6b1b](https://github.com/AllanLny/Lorexia/commit/6eb6b1b37707c9c93e1dbd384a7452a2553555f5))
* ui btn fix on note feature ([6bce1e8](https://github.com/AllanLny/Lorexia/commit/6bce1e8d7b80cf9b0e9bb5c5e45b7f9bb0a12340))
* ui to uses reusable component, and some fix ([5ebe2cd](https://github.com/AllanLny/Lorexia/commit/5ebe2cd68219c64466bfd8f28becceea0c4b9cbd))
* update all ci ([4d57008](https://github.com/AllanLny/Lorexia/commit/4d57008322349353d93dda6dd147d9e6f46dc550))
* update package-lock ([a1038b0](https://github.com/AllanLny/Lorexia/commit/a1038b0ece4f55094ccc10ea4e0550959ace5de3))
* update package-lock ([347af50](https://github.com/AllanLny/Lorexia/commit/347af50342784d17b98d9a95405f57ed97cad55a))
* update package-lock and add format-json script ([783a663](https://github.com/AllanLny/Lorexia/commit/783a66316860604281281488806ed35d29169c7e))


### Features

*  improve ui ([36a195b](https://github.com/AllanLny/Lorexia/commit/36a195b24e599ac7359d67aa62c05b7098d175b2))
* add autocompletion ([b578af5](https://github.com/AllanLny/Lorexia/commit/b578af5140461ece30439b8b38c218f1459f2cb2))
* add Hook to factory code ([62eda99](https://github.com/AllanLny/Lorexia/commit/62eda99d682b17f4672d8c1b92c5d064c26e0729))
* add ia verifier + improve ui ([0ab40a2](https://github.com/AllanLny/Lorexia/commit/0ab40a2b329394a5c98c0112cc7c4dee34e0ecdb))
* add logo ([f25a4f4](https://github.com/AllanLny/Lorexia/commit/f25a4f4421c8a537e822c5d98cff3a8f46358870))
* **datalogical:** improve app + improve data extraction logical ([fc0f35e](https://github.com/AllanLny/Lorexia/commit/fc0f35edb8eea1fc1523d1b7dd3e8d248de374bf))
* improve gitignore ([25963ec](https://github.com/AllanLny/Lorexia/commit/25963ec30e4ab35cbf8141a38969bfd1a910f91b))
* improve gitignore + add release possibility ([09b9918](https://github.com/AllanLny/Lorexia/commit/09b991858aac61606a99677abe16f50afd94bba5))
* improve ia setting modal ([facd0a5](https://github.com/AllanLny/Lorexia/commit/facd0a52580216a36001926ac07d3828c95ca5c4))
* qol upgrade ([8cf7f13](https://github.com/AllanLny/Lorexia/commit/8cf7f1371234c0e83c55ebbebfe729ea7ac8aab2))
* save pj now ([3b6f4da](https://github.com/AllanLny/Lorexia/commit/3b6f4da8576f388e77adb004e1a7e2831064993a))
* **ui:** implement automatic Ollama installer with React Portal modals ([e1d55f4](https://github.com/AllanLny/Lorexia/commit/e1d55f4c7e16fc141d8bdf93d6ded17a5133b19c))


### BREAKING CHANGES

* **ui:** Modal rendering now uses React Portal, requires #modal-root element

# 1.0.0 (2026-02-27)


### Bug Fixes

* add margin tob on tab nav ([3185648](https://github.com/AllanLny/Lorexia/commit/318564813d497c861d66cf10b8864be5842895cb))
* add scrool with keyboard for the autocompletion modal ([f3f249d](https://github.com/AllanLny/Lorexia/commit/f3f249d2c2c55841b7df17f03c5883b5e1fd7060))
* autocompletion improve ([ab95df1](https://github.com/AllanLny/Lorexia/commit/ab95df1c63635eabde70896822175c3ca9ac6ebb))
* change JDR Brain name to Lorexia ([d105b2f](https://github.com/AllanLny/Lorexia/commit/d105b2f054abedd2ad66b3c56adb402e137872cd))
* chat section to match with the app and improve UI/UX ([0cb41db](https://github.com/AllanLny/Lorexia/commit/0cb41db988f85d9116fc735f2e8e334c7ae33d7b))
* exclude flatpak builder on json ([05aaaa1](https://github.com/AllanLny/Lorexia/commit/05aaaa146192ee26db841d4ee1fbf538a6fe9299))
* fix e2e test ([e1bf71c](https://github.com/AllanLny/Lorexia/commit/e1bf71c1237390d30501daf21c865e65d8dd2a62))
* fix issues ([4051e8c](https://github.com/AllanLny/Lorexia/commit/4051e8c2daa198a9318d7b5e00acba6bd1ad78c0))
* logo and nav bar gap ([ec8c38f](https://github.com/AllanLny/Lorexia/commit/ec8c38ff4ab7f2e0cbdf28dd6bf31e8aa797d668))
* nouvelle sessions btn ui fix ([9aeec42](https://github.com/AllanLny/Lorexia/commit/9aeec4247ccd793a1ec71d07299eb5c99849db7a))
* package json ([6eb6b1b](https://github.com/AllanLny/Lorexia/commit/6eb6b1b37707c9c93e1dbd384a7452a2553555f5))
* ui btn fix on note feature ([6bce1e8](https://github.com/AllanLny/Lorexia/commit/6bce1e8d7b80cf9b0e9bb5c5e45b7f9bb0a12340))
* ui to uses reusable component, and some fix ([5ebe2cd](https://github.com/AllanLny/Lorexia/commit/5ebe2cd68219c64466bfd8f28becceea0c4b9cbd))
* update all ci ([4d57008](https://github.com/AllanLny/Lorexia/commit/4d57008322349353d93dda6dd147d9e6f46dc550))
* update package-lock ([a1038b0](https://github.com/AllanLny/Lorexia/commit/a1038b0ece4f55094ccc10ea4e0550959ace5de3))
* update package-lock ([347af50](https://github.com/AllanLny/Lorexia/commit/347af50342784d17b98d9a95405f57ed97cad55a))
* update package-lock and add format-json script ([783a663](https://github.com/AllanLny/Lorexia/commit/783a66316860604281281488806ed35d29169c7e))


### Features

*  improve ui ([36a195b](https://github.com/AllanLny/Lorexia/commit/36a195b24e599ac7359d67aa62c05b7098d175b2))
* add autocompletion ([b578af5](https://github.com/AllanLny/Lorexia/commit/b578af5140461ece30439b8b38c218f1459f2cb2))
* add Hook to factory code ([62eda99](https://github.com/AllanLny/Lorexia/commit/62eda99d682b17f4672d8c1b92c5d064c26e0729))
* add ia verifier + improve ui ([0ab40a2](https://github.com/AllanLny/Lorexia/commit/0ab40a2b329394a5c98c0112cc7c4dee34e0ecdb))
* add logo ([f25a4f4](https://github.com/AllanLny/Lorexia/commit/f25a4f4421c8a537e822c5d98cff3a8f46358870))
* **datalogical:** improve app + improve data extraction logical ([fc0f35e](https://github.com/AllanLny/Lorexia/commit/fc0f35edb8eea1fc1523d1b7dd3e8d248de374bf))
* improve gitignore ([25963ec](https://github.com/AllanLny/Lorexia/commit/25963ec30e4ab35cbf8141a38969bfd1a910f91b))
* improve gitignore + add release possibility ([09b9918](https://github.com/AllanLny/Lorexia/commit/09b991858aac61606a99677abe16f50afd94bba5))
* improve ia setting modal ([facd0a5](https://github.com/AllanLny/Lorexia/commit/facd0a52580216a36001926ac07d3828c95ca5c4))
* qol upgrade ([8cf7f13](https://github.com/AllanLny/Lorexia/commit/8cf7f1371234c0e83c55ebbebfe729ea7ac8aab2))
* save pj now ([3b6f4da](https://github.com/AllanLny/Lorexia/commit/3b6f4da8576f388e77adb004e1a7e2831064993a))
* **ui:** implement automatic Ollama installer with React Portal modals ([e1d55f4](https://github.com/AllanLny/Lorexia/commit/e1d55f4c7e16fc141d8bdf93d6ded17a5133b19c))


### BREAKING CHANGES

* **ui:** Modal rendering now uses React Portal, requires #modal-root element
