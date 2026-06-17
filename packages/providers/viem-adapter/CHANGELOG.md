# Changelog

## [1.0.0](https://github.com/substance-labs/cow-sdk/compare/sdk-viem-adapter-v0.3.24...sdk-viem-adapter-v1.0.0) (2026-06-17)


### ⚠ BREAKING CHANGES

* release cow-sdk v7

### ✨ Features

* add from/to fields for receipt ([#629](https://github.com/substance-labs/cow-sdk/issues/629)) ([3dd3868](https://github.com/substance-labs/cow-sdk/commit/3dd38682741ac93bfbd9b7d9a4fe79df7283dca0))
* add migration guide and wagmi example ([#498](https://github.com/substance-labs/cow-sdk/issues/498)) ([21be05d](https://github.com/substance-labs/cow-sdk/commit/21be05d5b6472de26120ebefe4626341af9a062d))
* add new order-signing features to adapters ([555d55f](https://github.com/substance-labs/cow-sdk/commit/555d55ff353376c11deef498b76795d5e7dcabca))
* **bridge:** add NearIntents bridge provider ([#663](https://github.com/substance-labs/cow-sdk/issues/663)) ([afd63bc](https://github.com/substance-labs/cow-sdk/commit/afd63bce3765e2adc81b73357e233399111e3595))
* **cow-shed:** add estimateGas method to SignerAdapters ([fbb626a](https://github.com/substance-labs/cow-sdk/commit/fbb626a0f88f6cb206432b4233b2d7d1e7cd4ad4))
* **cow-shed:** refact on common and contract-ts ([4be05aa](https://github.com/substance-labs/cow-sdk/commit/4be05aa7a376fbc7d2ed5b2d2b6b68e3630b9c59))
* enhance adapters and utils with composable features ([8691d42](https://github.com/substance-labs/cow-sdk/commit/8691d42b8076c7d240a97e6808902f6d8742bcd3))
* enhance composable to test the 3 adapters ([7d1bd77](https://github.com/substance-labs/cow-sdk/commit/7d1bd776b40a10808b9f6392dda862f610131169))
* implement adapters for ethers v5, ethers v6, and viem ([1231f7c](https://github.com/substance-labs/cow-sdk/commit/1231f7c1809fd497d15e8945b880a9c3da6fa6b4))
* **lib-agnostic:** migrate latest SDK changes ([#427](https://github.com/substance-labs/cow-sdk/issues/427)) ([323bab6](https://github.com/substance-labs/cow-sdk/commit/323bab61eb5adeb4a58bc15e25ffb29d2e1afcbf))
* release cow-sdk v7 ([6cd3e57](https://github.com/substance-labs/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))
* **sdk-agnostic-lib:** Add composable package ([bf3f864](https://github.com/substance-labs/cow-sdk/commit/bf3f864815326813bbb18d2d98d10345d9aa6a2b))
* **sdk-agnostic-lib:** create app data package ([#327](https://github.com/substance-labs/cow-sdk/issues/327)) ([8b61261](https://github.com/substance-labs/cow-sdk/commit/8b612615bc280dee2e5f4767794bc03f590d4764))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/substance-labs/cow-sdk/issues/368)) ([0a4534a](https://github.com/substance-labs/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/substance-labs/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/substance-labs/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))
* update adapters with new contracts-ts features ([aadd9a7](https://github.com/substance-labs/cow-sdk/commit/aadd9a74771876c21339bfb4731654656a325d96))
* update adapters with new contracts-ts features ([fc94704](https://github.com/substance-labs/cow-sdk/commit/fc947043316a603e64f3c3d4b07178169d21a9a6))


### 🐛 Bug Fixes

* **cow-shed:** fix adapters - estimateGas  and encodeAbi ([76ab995](https://github.com/substance-labs/cow-sdk/commit/76ab995635247e63213dafb50ff462334977cc6d))
* improve unknown/any types ([#443](https://github.com/substance-labs/cow-sdk/issues/443)) ([e6b8a40](https://github.com/substance-labs/cow-sdk/commit/e6b8a40578583cf6d1ecd208434782422f308ef0))
* **lib-agnostic:** add setProvider() method to adapters ([#432](https://github.com/substance-labs/cow-sdk/issues/432)) ([64c0ea9](https://github.com/substance-labs/cow-sdk/commit/64c0ea94d802aa167b978ae0859353d801de0911))
* **trading:** add EIP1271 signature support ([#584](https://github.com/substance-labs/cow-sdk/issues/584)) ([ca9e834](https://github.com/substance-labs/cow-sdk/commit/ca9e834e2b0edf8a757e01383b2218d5ecfbe25e))
* **viem-adapter:** hex-encode value in estimateGas ([#884](https://github.com/substance-labs/cow-sdk/issues/884)) ([fb932fa](https://github.com/substance-labs/cow-sdk/commit/fb932fa6d59966186c591823951a891a58f90047))
* viemUtils encodeAbi ([c5698dd](https://github.com/substance-labs/cow-sdk/commit/c5698ddc14bbcd68e88440b50c40f4c927beccb7))


### 📚 Documentation

* remove info about umbrella sdk ([#874](https://github.com/substance-labs/cow-sdk/issues/874)) ([bb0280e](https://github.com/substance-labs/cow-sdk/commit/bb0280e7bfcdd6c2d7b122baf43910d9e4e4299f))


### 🔧 Miscellaneous

* fix typing issue ([#885](https://github.com/substance-labs/cow-sdk/issues/885)) ([73d6d95](https://github.com/substance-labs/cow-sdk/commit/73d6d95082f8d8b8ec62de6ccbf72f43fccc0f41))
* release main ([#453](https://github.com/substance-labs/cow-sdk/issues/453)) ([36080c1](https://github.com/substance-labs/cow-sdk/commit/36080c1955f5f161bebce7867af110f6938e5c95))
* release main ([#467](https://github.com/substance-labs/cow-sdk/issues/467)) ([ed2977a](https://github.com/substance-labs/cow-sdk/commit/ed2977a82bb2f4b43de900840848e33532d001f0))
* release main ([#488](https://github.com/substance-labs/cow-sdk/issues/488)) ([6344fa6](https://github.com/substance-labs/cow-sdk/commit/6344fa619465e6f94637677823a18646f06fa7c9))
* release main ([#491](https://github.com/substance-labs/cow-sdk/issues/491)) ([bf28181](https://github.com/substance-labs/cow-sdk/commit/bf281814844e0f9b5ad1cd1f5b12f89e6bea3a5a))
* release main ([#503](https://github.com/substance-labs/cow-sdk/issues/503)) ([532d8eb](https://github.com/substance-labs/cow-sdk/commit/532d8eb2a0a0f9ec5775e566fe2507f1ccc4f961))
* release main ([#511](https://github.com/substance-labs/cow-sdk/issues/511)) ([5629bb2](https://github.com/substance-labs/cow-sdk/commit/5629bb25f89b62e490b9819393036994688bf648))
* release main ([#515](https://github.com/substance-labs/cow-sdk/issues/515)) ([912e315](https://github.com/substance-labs/cow-sdk/commit/912e31551440ebfa61d7d2f5c846d61162559448))
* release main ([#542](https://github.com/substance-labs/cow-sdk/issues/542)) ([e9f98a6](https://github.com/substance-labs/cow-sdk/commit/e9f98a623cf81f4a9246550999914c88eb1fca30))
* release main ([#575](https://github.com/substance-labs/cow-sdk/issues/575)) ([2ef068b](https://github.com/substance-labs/cow-sdk/commit/2ef068b851e5d114784f81ecbcd0fe3c512b7570))
* release main ([#605](https://github.com/substance-labs/cow-sdk/issues/605)) ([c9efd22](https://github.com/substance-labs/cow-sdk/commit/c9efd22e6c934e95cb0e88a684b3a973b7ac3cce))
* release main ([#620](https://github.com/substance-labs/cow-sdk/issues/620)) ([b36394a](https://github.com/substance-labs/cow-sdk/commit/b36394a2ba38957edb47ffc4451ea6624d66737b))
* release main ([#635](https://github.com/substance-labs/cow-sdk/issues/635)) ([bd5c1d9](https://github.com/substance-labs/cow-sdk/commit/bd5c1d998c17379b2386942a0404ad4e0e232b4c))
* release main ([#700](https://github.com/substance-labs/cow-sdk/issues/700)) ([a0ce28d](https://github.com/substance-labs/cow-sdk/commit/a0ce28d18e51b50e947bc104228686d558861391))
* release main ([#772](https://github.com/substance-labs/cow-sdk/issues/772)) ([cd30d4f](https://github.com/substance-labs/cow-sdk/commit/cd30d4fe42c4b2d1bbe592026a097d6b76edd735))
* release main ([#780](https://github.com/substance-labs/cow-sdk/issues/780)) ([3fa1e95](https://github.com/substance-labs/cow-sdk/commit/3fa1e951c248fb8c72c7b7a3cd2e96470e1582df))
* release main ([#784](https://github.com/substance-labs/cow-sdk/issues/784)) ([8284aa4](https://github.com/substance-labs/cow-sdk/commit/8284aa47954ab4880b6bd87b4b09f23656b264fd))
* release main ([#788](https://github.com/substance-labs/cow-sdk/issues/788)) ([9d7eecb](https://github.com/substance-labs/cow-sdk/commit/9d7eecb86b40c15ea2c368c02213e166ea9b6cd2))
* release main ([#790](https://github.com/substance-labs/cow-sdk/issues/790)) ([4109197](https://github.com/substance-labs/cow-sdk/commit/410919754c2f07e99a92787bf7b3c503ac34c9ea))
* release main ([#794](https://github.com/substance-labs/cow-sdk/issues/794)) ([6f11dfd](https://github.com/substance-labs/cow-sdk/commit/6f11dfdca4cecee7d036fc2ae49c886832db25bf))
* release main ([#802](https://github.com/substance-labs/cow-sdk/issues/802)) ([5583ca4](https://github.com/substance-labs/cow-sdk/commit/5583ca446f498416565b79485bcaf7708f1ba224))
* release main ([#805](https://github.com/substance-labs/cow-sdk/issues/805)) ([adbc6a9](https://github.com/substance-labs/cow-sdk/commit/adbc6a98eb15b02a87215a1bd446982553219b41))
* release main ([#811](https://github.com/substance-labs/cow-sdk/issues/811)) ([816c990](https://github.com/substance-labs/cow-sdk/commit/816c990e87a39a122c918d6748b2f254350c4be5))
* release main ([#812](https://github.com/substance-labs/cow-sdk/issues/812)) ([4981e10](https://github.com/substance-labs/cow-sdk/commit/4981e1060718f701ad3a6a096e71ef2e544f29fe))
* release main ([#819](https://github.com/substance-labs/cow-sdk/issues/819)) ([5f7ecfb](https://github.com/substance-labs/cow-sdk/commit/5f7ecfba74abc721b80c5fe6f4997f9518c40788))
* release main ([#826](https://github.com/substance-labs/cow-sdk/issues/826)) ([baaa708](https://github.com/substance-labs/cow-sdk/commit/baaa7088ac15b89fb83310e54aa52f09d19132ff))
* release main ([#832](https://github.com/substance-labs/cow-sdk/issues/832)) ([5dafcb8](https://github.com/substance-labs/cow-sdk/commit/5dafcb8ec5593250dba1ff6e9fdbf8eb11d974cf))
* release main ([#836](https://github.com/substance-labs/cow-sdk/issues/836)) ([a7e1af9](https://github.com/substance-labs/cow-sdk/commit/a7e1af993f501e313fb90573148b3d2d42e5168a))
* release main ([#840](https://github.com/substance-labs/cow-sdk/issues/840)) ([1a22c69](https://github.com/substance-labs/cow-sdk/commit/1a22c69592e283bb1a15ece9799a5b6f8c446765))
* release main ([#842](https://github.com/substance-labs/cow-sdk/issues/842)) ([c4c238d](https://github.com/substance-labs/cow-sdk/commit/c4c238d990d2089a66f9d8dc7401cd71b63d394b))
* release main ([#848](https://github.com/substance-labs/cow-sdk/issues/848)) ([a56dead](https://github.com/substance-labs/cow-sdk/commit/a56dead934dd2d7d72583d996ea9f61e6091534b))
* release main ([#857](https://github.com/substance-labs/cow-sdk/issues/857)) ([17fcfc5](https://github.com/substance-labs/cow-sdk/commit/17fcfc590be8529dc4fe05b1c472fef1b07b47f4))
* release main ([#861](https://github.com/substance-labs/cow-sdk/issues/861)) ([c178e68](https://github.com/substance-labs/cow-sdk/commit/c178e68beaf46bb33b1ad2ec97212eec62172816))
* release main ([#864](https://github.com/substance-labs/cow-sdk/issues/864)) ([a5207e0](https://github.com/substance-labs/cow-sdk/commit/a5207e0dba212942ecf5564c8d01c9c75c77f647))
* release main ([#880](https://github.com/substance-labs/cow-sdk/issues/880)) ([447b5e1](https://github.com/substance-labs/cow-sdk/commit/447b5e17b36a800a5f6fe6e4f890d2d77d017495))
* release main ([#886](https://github.com/substance-labs/cow-sdk/issues/886)) ([5115efe](https://github.com/substance-labs/cow-sdk/commit/5115efeb6f6f591c5eae653c63c5c5930eb24331))
* release main ([#887](https://github.com/substance-labs/cow-sdk/issues/887)) ([74393ee](https://github.com/substance-labs/cow-sdk/commit/74393ee2923a2932584998169daca6ce3c2da60c))
* release main ([#889](https://github.com/substance-labs/cow-sdk/issues/889)) ([8659102](https://github.com/substance-labs/cow-sdk/commit/865910213586d59f709c8e34726f799503bdfafb))
* release main ([#894](https://github.com/substance-labs/cow-sdk/issues/894)) ([6ca7944](https://github.com/substance-labs/cow-sdk/commit/6ca794476e3411ab5a3774d6cd88804b9f875d29))
* release main ([#900](https://github.com/substance-labs/cow-sdk/issues/900)) ([3fdbda2](https://github.com/substance-labs/cow-sdk/commit/3fdbda2042db284c73e3b16b90961e1c31a475cd))
* revert release ([#634](https://github.com/substance-labs/cow-sdk/issues/634)) ([fc7bf61](https://github.com/substance-labs/cow-sdk/commit/fc7bf61444619d4b2c3a3dd55b7ce52c197b1878))
* revert release ([#833](https://github.com/substance-labs/cow-sdk/issues/833)) ([0c40a9b](https://github.com/substance-labs/cow-sdk/commit/0c40a9b3ee828c7ede66576f02e1b571e96140cd))
* **sdk-agnostic-lib:** improve scripts and types ([#407](https://github.com/substance-labs/cow-sdk/issues/407)) ([c4b5e08](https://github.com/substance-labs/cow-sdk/commit/c4b5e086ce46086e9430d5f03ed330502349fbf3))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/substance-labs/cow-sdk/issues/354)) ([55d3068](https://github.com/substance-labs/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 1.0.0

## [0.3.24](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.23...sdk-viem-adapter-v0.3.24) (2026-06-15)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.12.0

## [0.3.23](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.22...sdk-viem-adapter-v0.3.23) (2026-06-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.2

## [0.3.22](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.21...sdk-viem-adapter-v0.3.22) (2026-06-02)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.1

## [0.3.21](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.20...sdk-viem-adapter-v0.3.21) (2026-05-27)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.0

## [0.3.20](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.19...sdk-viem-adapter-v0.3.20) (2026-05-22)


### 🔧 Miscellaneous

* fix typing issue ([#885](https://github.com/cowprotocol/cow-sdk/issues/885)) ([73d6d95](https://github.com/cowprotocol/cow-sdk/commit/73d6d95082f8d8b8ec62de6ccbf72f43fccc0f41))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.3

## [0.3.19](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.18...sdk-viem-adapter-v0.3.19) (2026-05-20)


### 🐛 Bug Fixes

* **viem-adapter:** hex-encode value in estimateGas ([#884](https://github.com/cowprotocol/cow-sdk/issues/884)) ([fb932fa](https://github.com/cowprotocol/cow-sdk/commit/fb932fa6d59966186c591823951a891a58f90047))


### 📚 Documentation

* remove info about umbrella sdk ([#874](https://github.com/cowprotocol/cow-sdk/issues/874)) ([bb0280e](https://github.com/cowprotocol/cow-sdk/commit/bb0280e7bfcdd6c2d7b122baf43910d9e4e4299f))

## [0.3.18](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.17...sdk-viem-adapter-v0.3.18) (2026-04-16)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.2

## [0.3.17](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.16...sdk-viem-adapter-v0.3.17) (2026-04-14)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.1

## [0.3.16](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.15...sdk-viem-adapter-v0.3.16) (2026-04-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.0

## [0.3.15](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.14...sdk-viem-adapter-v0.3.15) (2026-04-01)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.9.0

## [0.3.14](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.13...sdk-viem-adapter-v0.3.14) (2026-03-17)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.2

## [0.3.13](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.12...sdk-viem-adapter-v0.3.13) (2026-03-16)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.1

## [0.3.12](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.11...sdk-viem-adapter-v0.3.12) (2026-03-16)


### 🔧 Miscellaneous

* release main ([#826](https://github.com/cowprotocol/cow-sdk/issues/826)) ([baaa708](https://github.com/cowprotocol/cow-sdk/commit/baaa7088ac15b89fb83310e54aa52f09d19132ff))
* release main ([#832](https://github.com/cowprotocol/cow-sdk/issues/832)) ([5dafcb8](https://github.com/cowprotocol/cow-sdk/commit/5dafcb8ec5593250dba1ff6e9fdbf8eb11d974cf))
* revert release ([#833](https://github.com/cowprotocol/cow-sdk/issues/833)) ([0c40a9b](https://github.com/cowprotocol/cow-sdk/commit/0c40a9b3ee828c7ede66576f02e1b571e96140cd))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.0

## [0.3.11](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.10...sdk-viem-adapter-v0.3.11) (2026-03-10)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.7.1

## [0.3.10](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.9...sdk-viem-adapter-v0.3.10) (2026-03-04)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.7.0

## [0.3.9](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.8...sdk-viem-adapter-v0.3.9) (2026-03-04)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.3

## [0.3.8](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.7...sdk-viem-adapter-v0.3.8) (2026-02-20)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.2

## [0.3.7](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.6...sdk-viem-adapter-v0.3.7) (2026-02-18)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.1

## [0.3.6](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.5...sdk-viem-adapter-v0.3.6) (2026-02-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.0

## [0.3.5](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.4...sdk-viem-adapter-v0.3.5) (2026-02-02)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.4

## [0.3.4](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.3...sdk-viem-adapter-v0.3.4) (2026-02-02)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.3

## [0.3.3](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.2...sdk-viem-adapter-v0.3.3) (2026-01-28)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.2

## [0.3.2](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.1...sdk-viem-adapter-v0.3.2) (2026-01-28)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.1

## [0.3.1](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.0...sdk-viem-adapter-v0.3.1) (2026-01-19)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.0

## [0.3.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.2.0...sdk-viem-adapter-v0.3.0) (2025-11-24)


### ✨ Features

* **bridge:** add NearIntents bridge provider ([#663](https://github.com/cowprotocol/cow-sdk/issues/663)) ([afd63bc](https://github.com/cowprotocol/cow-sdk/commit/afd63bce3765e2adc81b73357e233399111e3595))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.4.0

## [0.2.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.1.3...sdk-viem-adapter-v0.2.0) (2025-10-29)


### ✨ Features

* add from/to fields for receipt ([#629](https://github.com/cowprotocol/cow-sdk/issues/629)) ([3dd3868](https://github.com/cowprotocol/cow-sdk/commit/3dd38682741ac93bfbd9b7d9a4fe79df7283dca0))


### 🔧 Miscellaneous

* release main ([#620](https://github.com/cowprotocol/cow-sdk/issues/620)) ([b36394a](https://github.com/cowprotocol/cow-sdk/commit/b36394a2ba38957edb47ffc4451ea6624d66737b))
* revert release ([#634](https://github.com/cowprotocol/cow-sdk/issues/634)) ([fc7bf61](https://github.com/cowprotocol/cow-sdk/commit/fc7bf61444619d4b2c3a3dd55b7ce52c197b1878))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.3.0

## [0.1.3](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.1.2...sdk-viem-adapter-v0.1.3) (2025-10-24)


### 🐛 Bug Fixes

* **trading:** add EIP1271 signature support ([#584](https://github.com/cowprotocol/cow-sdk/issues/584)) ([ca9e834](https://github.com/cowprotocol/cow-sdk/commit/ca9e834e2b0edf8a757e01383b2218d5ecfbe25e))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.2

## [0.1.2](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.1.1...sdk-viem-adapter-v0.1.2) (2025-10-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.1

## [0.1.1](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.1.0...sdk-viem-adapter-v0.1.1) (2025-10-06)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.0

## [0.1.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.1-beta.0...sdk-viem-adapter-v0.1.0) (2025-09-17)


### ⚠ BREAKING CHANGES

* release cow-sdk v7

### ✨ Features

* release cow-sdk v7 ([6cd3e57](https://github.com/cowprotocol/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.1.0

## [0.3.1-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.3.0-beta.0...sdk-viem-adapter-v0.3.1-beta.0) (2025-09-17)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.0-beta.0

## [0.3.0-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.2.2-beta.0...sdk-viem-adapter-v0.3.0-beta.0) (2025-09-16)


### ✨ Features

* add migration guide and wagmi example ([#498](https://github.com/cowprotocol/cow-sdk/issues/498)) ([21be05d](https://github.com/cowprotocol/cow-sdk/commit/21be05d5b6472de26120ebefe4626341af9a062d))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.4.0-beta.0

## [0.2.2-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.2.1-beta.0...sdk-viem-adapter-v0.2.2-beta.0) (2025-09-11)


### 🔧 Miscellaneous

* release main ([#488](https://github.com/cowprotocol/cow-sdk/issues/488)) ([6344fa6](https://github.com/cowprotocol/cow-sdk/commit/6344fa619465e6f94637677823a18646f06fa7c9))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.3.0-beta.0

## [0.2.1-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.2.0-beta.0...sdk-viem-adapter-v0.2.1-beta.0) (2025-09-01)


### 🐛 Bug Fixes

* improve unknown/any types ([#443](https://github.com/cowprotocol/cow-sdk/issues/443)) ([e6b8a40](https://github.com/cowprotocol/cow-sdk/commit/e6b8a40578583cf6d1ecd208434782422f308ef0))

## [0.2.0-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-viem-adapter-v0.1.0-beta.0...sdk-viem-adapter-v0.2.0-beta.0) (2025-08-28)


### ✨ Features

* add new order-signing features to adapters ([555d55f](https://github.com/cowprotocol/cow-sdk/commit/555d55ff353376c11deef498b76795d5e7dcabca))
* allow changing backoff and limiter per request ([#208](https://github.com/cowprotocol/cow-sdk/issues/208)) ([ebea5ca](https://github.com/cowprotocol/cow-sdk/commit/ebea5ca0858aeb89ae3e5d5407c8903c3ca5178d))
* **cow-shed:** add estimateGas method to SignerAdapters ([fbb626a](https://github.com/cowprotocol/cow-sdk/commit/fbb626a0f88f6cb206432b4233b2d7d1e7cd4ad4))
* **cow-shed:** refact on common and contract-ts ([4be05aa](https://github.com/cowprotocol/cow-sdk/commit/4be05aa7a376fbc7d2ed5b2d2b6b68e3630b9c59))
* enhance adapters and utils with composable features ([8691d42](https://github.com/cowprotocol/cow-sdk/commit/8691d42b8076c7d240a97e6808902f6d8742bcd3))
* enhance composable to test the 3 adapters ([7d1bd77](https://github.com/cowprotocol/cow-sdk/commit/7d1bd776b40a10808b9f6392dda862f610131169))
* implement adapters for ethers v5, ethers v6, and viem ([1231f7c](https://github.com/cowprotocol/cow-sdk/commit/1231f7c1809fd497d15e8945b880a9c3da6fa6b4))
* **lib-agnostic:** migrate latest SDK changes ([#427](https://github.com/cowprotocol/cow-sdk/issues/427)) ([323bab6](https://github.com/cowprotocol/cow-sdk/commit/323bab61eb5adeb4a58bc15e25ffb29d2e1afcbf))
* **sdk-agnostic-lib:** create app data package ([#327](https://github.com/cowprotocol/cow-sdk/issues/327)) ([8b61261](https://github.com/cowprotocol/cow-sdk/commit/8b612615bc280dee2e5f4767794bc03f590d4764))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/cowprotocol/cow-sdk/issues/368)) ([0a4534a](https://github.com/cowprotocol/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/cowprotocol/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/cowprotocol/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))
* update adapters with new contracts-ts features ([aadd9a7](https://github.com/cowprotocol/cow-sdk/commit/aadd9a74771876c21339bfb4731654656a325d96))
* update adapters with new contracts-ts features ([fc94704](https://github.com/cowprotocol/cow-sdk/commit/fc947043316a603e64f3c3d4b07178169d21a9a6))


### 🐛 Bug Fixes

* **cow-shed:** fix adapters - estimateGas  and encodeAbi ([76ab995](https://github.com/cowprotocol/cow-sdk/commit/76ab995635247e63213dafb50ff462334977cc6d))
* **lib-agnostic:** add setProvider() method to adapters ([#432](https://github.com/cowprotocol/cow-sdk/issues/432)) ([64c0ea9](https://github.com/cowprotocol/cow-sdk/commit/64c0ea94d802aa167b978ae0859353d801de0911))
* viemUtils encodeAbi ([c5698dd](https://github.com/cowprotocol/cow-sdk/commit/c5698ddc14bbcd68e88440b50c40f4c927beccb7))


### 🔧 Miscellaneous

* **sdk-agnostic-lib:** improve scripts and types ([#407](https://github.com/cowprotocol/cow-sdk/issues/407)) ([c4b5e08](https://github.com/cowprotocol/cow-sdk/commit/c4b5e086ce46086e9430d5f03ed330502349fbf3))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/cowprotocol/cow-sdk/issues/354)) ([55d3068](https://github.com/cowprotocol/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))
