# Changelog

## [2.0.0](https://github.com/substance-labs/cow-sdk/compare/sdk-order-signing-v1.1.0...sdk-order-signing-v2.0.0) (2026-06-17)


### ⚠ BREAKING CHANGES

* bring cow.fi back ([#863](https://github.com/substance-labs/cow-sdk/issues/863))
* release cow-sdk v7

### ✨ Features

* bring cow.fi back ([#863](https://github.com/substance-labs/cow-sdk/issues/863)) ([d607fd2](https://github.com/substance-labs/cow-sdk/commit/d607fd2cfbc93ace39de04f3a7870f723fdd9b21))
* migrate to cow.finance domain ([#860](https://github.com/substance-labs/cow-sdk/issues/860)) ([a4e7633](https://github.com/substance-labs/cow-sdk/commit/a4e76333b7a276baec5c977f44b15498550d8e50))
* move order-signing to new package ([c60daab](https://github.com/substance-labs/cow-sdk/commit/c60daabcd3e9311913f27b519561b7b992958cf4))
* per-package test coverage badges, updated in CI ([#895](https://github.com/substance-labs/cow-sdk/issues/895)) ([c73246c](https://github.com/substance-labs/cow-sdk/commit/c73246cc52c4fc79b2628b7c5f580695fd3dc1e2))
* refactor order-signing ([8e28d1b](https://github.com/substance-labs/cow-sdk/commit/8e28d1bdbda9632347cacaae906298e736f4a7b3))
* refactor order-signing tests ([2d99282](https://github.com/substance-labs/cow-sdk/commit/2d99282382da1545cd205cf246db0f055e7e0415))
* release cow-sdk v7 ([6cd3e57](https://github.com/substance-labs/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/substance-labs/cow-sdk/issues/368)) ([0a4534a](https://github.com/substance-labs/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/substance-labs/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/substance-labs/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))
* simplify OrderSigningUtils to use static methods only ([#417](https://github.com/substance-labs/cow-sdk/issues/417)) ([899ca43](https://github.com/substance-labs/cow-sdk/commit/899ca4325be831b6711468d1df3733d98fe913b0))
* update settlement and vault relayer contracts on staging ([#807](https://github.com/substance-labs/cow-sdk/issues/807)) ([0f9a03e](https://github.com/substance-labs/cow-sdk/commit/0f9a03e6bfa3468630e46735f7583618ae711b73))


### 🐛 Bug Fixes

* **lib-agnostic:** add setProvider() method to adapters ([#432](https://github.com/substance-labs/cow-sdk/issues/432)) ([64c0ea9](https://github.com/substance-labs/cow-sdk/commit/64c0ea94d802aa167b978ae0859353d801de0911))
* **trading:** add EIP1271 signature support ([#584](https://github.com/substance-labs/cow-sdk/issues/584)) ([ca9e834](https://github.com/substance-labs/cow-sdk/commit/ca9e834e2b0edf8a757e01383b2218d5ecfbe25e))


### 📚 Documentation

* update README to focus on main use cases ([#493](https://github.com/substance-labs/cow-sdk/issues/493)) ([a05cb1b](https://github.com/substance-labs/cow-sdk/commit/a05cb1ba11b5f9895d7cfe6262cf74c4089fd73c))


### 🔧 Miscellaneous

* release main ([#453](https://github.com/substance-labs/cow-sdk/issues/453)) ([36080c1](https://github.com/substance-labs/cow-sdk/commit/36080c1955f5f161bebce7867af110f6938e5c95))
* release main ([#486](https://github.com/substance-labs/cow-sdk/issues/486)) ([cf53df2](https://github.com/substance-labs/cow-sdk/commit/cf53df2d0f5e96a544165547958ecc959c1948d7))
* release main ([#488](https://github.com/substance-labs/cow-sdk/issues/488)) ([6344fa6](https://github.com/substance-labs/cow-sdk/commit/6344fa619465e6f94637677823a18646f06fa7c9))
* release main ([#491](https://github.com/substance-labs/cow-sdk/issues/491)) ([bf28181](https://github.com/substance-labs/cow-sdk/commit/bf281814844e0f9b5ad1cd1f5b12f89e6bea3a5a))
* release main ([#497](https://github.com/substance-labs/cow-sdk/issues/497)) ([7d97945](https://github.com/substance-labs/cow-sdk/commit/7d979459a2febdee59f98570fbd2271c4c61d0df))
* release main ([#500](https://github.com/substance-labs/cow-sdk/issues/500)) ([76c5185](https://github.com/substance-labs/cow-sdk/commit/76c5185d4b827d185af11bef9435fbed87484b0b))
* release main ([#502](https://github.com/substance-labs/cow-sdk/issues/502)) ([c452d8e](https://github.com/substance-labs/cow-sdk/commit/c452d8e53bc0dcd79052b1877d2c48a32777093e))
* release main ([#503](https://github.com/substance-labs/cow-sdk/issues/503)) ([532d8eb](https://github.com/substance-labs/cow-sdk/commit/532d8eb2a0a0f9ec5775e566fe2507f1ccc4f961))
* release main ([#505](https://github.com/substance-labs/cow-sdk/issues/505)) ([0f98564](https://github.com/substance-labs/cow-sdk/commit/0f985640c6e6f0852505cb3ad66c07bd3f23ea7b))
* release main ([#511](https://github.com/substance-labs/cow-sdk/issues/511)) ([5629bb2](https://github.com/substance-labs/cow-sdk/commit/5629bb25f89b62e490b9819393036994688bf648))
* release main ([#515](https://github.com/substance-labs/cow-sdk/issues/515)) ([912e315](https://github.com/substance-labs/cow-sdk/commit/912e31551440ebfa61d7d2f5c846d61162559448))
* release main ([#524](https://github.com/substance-labs/cow-sdk/issues/524)) ([78c209b](https://github.com/substance-labs/cow-sdk/commit/78c209bc5feeb90007bd9043dc5be861fed2d0ac))
* release main ([#532](https://github.com/substance-labs/cow-sdk/issues/532)) ([762ebd8](https://github.com/substance-labs/cow-sdk/commit/762ebd8a17fbec8a452e62c52e8efb5cd9d3070b))
* release main ([#534](https://github.com/substance-labs/cow-sdk/issues/534)) ([cb65e65](https://github.com/substance-labs/cow-sdk/commit/cb65e653925d0ef1942428738e74046b61c0020a))
* release main ([#542](https://github.com/substance-labs/cow-sdk/issues/542)) ([e9f98a6](https://github.com/substance-labs/cow-sdk/commit/e9f98a623cf81f4a9246550999914c88eb1fca30))
* release main ([#575](https://github.com/substance-labs/cow-sdk/issues/575)) ([2ef068b](https://github.com/substance-labs/cow-sdk/commit/2ef068b851e5d114784f81ecbcd0fe3c512b7570))
* release main ([#581](https://github.com/substance-labs/cow-sdk/issues/581)) ([0f09262](https://github.com/substance-labs/cow-sdk/commit/0f0926297da8949de97379e7300a1e5301bde724))
* release main ([#605](https://github.com/substance-labs/cow-sdk/issues/605)) ([c9efd22](https://github.com/substance-labs/cow-sdk/commit/c9efd22e6c934e95cb0e88a684b3a973b7ac3cce))
* release main ([#620](https://github.com/substance-labs/cow-sdk/issues/620)) ([b36394a](https://github.com/substance-labs/cow-sdk/commit/b36394a2ba38957edb47ffc4451ea6624d66737b))
* release main ([#635](https://github.com/substance-labs/cow-sdk/issues/635)) ([bd5c1d9](https://github.com/substance-labs/cow-sdk/commit/bd5c1d998c17379b2386942a0404ad4e0e232b4c))
* release main ([#637](https://github.com/substance-labs/cow-sdk/issues/637)) ([6909e8d](https://github.com/substance-labs/cow-sdk/commit/6909e8d5e97afadc203be2293865bfb2f9338953))
* release main ([#648](https://github.com/substance-labs/cow-sdk/issues/648)) ([5dd3bf5](https://github.com/substance-labs/cow-sdk/commit/5dd3bf5659852590d5d46317bfc19c56e125ca59))
* release main ([#650](https://github.com/substance-labs/cow-sdk/issues/650)) ([2493612](https://github.com/substance-labs/cow-sdk/commit/24936120e51b0083eda408ab80b8f8ee4115e223))
* release main ([#700](https://github.com/substance-labs/cow-sdk/issues/700)) ([a0ce28d](https://github.com/substance-labs/cow-sdk/commit/a0ce28d18e51b50e947bc104228686d558861391))
* release main ([#702](https://github.com/substance-labs/cow-sdk/issues/702)) ([1e6b54d](https://github.com/substance-labs/cow-sdk/commit/1e6b54dbaef21a61c362bc2d1567d87f14d7f8a7))
* release main ([#718](https://github.com/substance-labs/cow-sdk/issues/718)) ([87683ec](https://github.com/substance-labs/cow-sdk/commit/87683ecc507e59d70a6d623faba83cda65ca44cc))
* release main ([#720](https://github.com/substance-labs/cow-sdk/issues/720)) ([c7348b8](https://github.com/substance-labs/cow-sdk/commit/c7348b8eeaddb371c82631dbf94bfd8b0fb0209b))
* release main ([#721](https://github.com/substance-labs/cow-sdk/issues/721)) ([d8cb9ec](https://github.com/substance-labs/cow-sdk/commit/d8cb9ec16d16af35f8c2a1387b82fee472acd380))
* release main ([#727](https://github.com/substance-labs/cow-sdk/issues/727)) ([af17e9a](https://github.com/substance-labs/cow-sdk/commit/af17e9a772f608c5c2751bce25549062a38702b6))
* release main ([#730](https://github.com/substance-labs/cow-sdk/issues/730)) ([e7e4157](https://github.com/substance-labs/cow-sdk/commit/e7e415700724d6cc62f1f0590dbf47d908a9a55e))
* release main ([#735](https://github.com/substance-labs/cow-sdk/issues/735)) ([c17655c](https://github.com/substance-labs/cow-sdk/commit/c17655c588a735bd12c1219317f5b290cf9d9a34))
* release main ([#741](https://github.com/substance-labs/cow-sdk/issues/741)) ([32fb8bb](https://github.com/substance-labs/cow-sdk/commit/32fb8bbe6b1172c2666f330d0d50cdc2f7c2554f))
* release main ([#742](https://github.com/substance-labs/cow-sdk/issues/742)) ([8c8d857](https://github.com/substance-labs/cow-sdk/commit/8c8d857e9c9da59b8793f2f9dfb3ca075891e6e3))
* release main ([#744](https://github.com/substance-labs/cow-sdk/issues/744)) ([110c279](https://github.com/substance-labs/cow-sdk/commit/110c279db08dd981c0bda2c6b7e8c08ea3c81325))
* release main ([#751](https://github.com/substance-labs/cow-sdk/issues/751)) ([885d7f7](https://github.com/substance-labs/cow-sdk/commit/885d7f707bf2074dfb80df6ebcf41c12515695e3))
* release main ([#754](https://github.com/substance-labs/cow-sdk/issues/754)) ([3f2f53c](https://github.com/substance-labs/cow-sdk/commit/3f2f53cdf66520d2f2c8fd82df2b614bc202eb6b))
* release main ([#772](https://github.com/substance-labs/cow-sdk/issues/772)) ([cd30d4f](https://github.com/substance-labs/cow-sdk/commit/cd30d4fe42c4b2d1bbe592026a097d6b76edd735))
* release main ([#778](https://github.com/substance-labs/cow-sdk/issues/778)) ([d84e4a3](https://github.com/substance-labs/cow-sdk/commit/d84e4a3a5d918a6ba28879a20798510eb84cbf12))
* release main ([#779](https://github.com/substance-labs/cow-sdk/issues/779)) ([6387df5](https://github.com/substance-labs/cow-sdk/commit/6387df570750f4411ad57e3aed709b4eb848557c))
* release main ([#780](https://github.com/substance-labs/cow-sdk/issues/780)) ([3fa1e95](https://github.com/substance-labs/cow-sdk/commit/3fa1e951c248fb8c72c7b7a3cd2e96470e1582df))
* release main ([#784](https://github.com/substance-labs/cow-sdk/issues/784)) ([8284aa4](https://github.com/substance-labs/cow-sdk/commit/8284aa47954ab4880b6bd87b4b09f23656b264fd))
* release main ([#788](https://github.com/substance-labs/cow-sdk/issues/788)) ([9d7eecb](https://github.com/substance-labs/cow-sdk/commit/9d7eecb86b40c15ea2c368c02213e166ea9b6cd2))
* release main ([#790](https://github.com/substance-labs/cow-sdk/issues/790)) ([4109197](https://github.com/substance-labs/cow-sdk/commit/410919754c2f07e99a92787bf7b3c503ac34c9ea))
* release main ([#794](https://github.com/substance-labs/cow-sdk/issues/794)) ([6f11dfd](https://github.com/substance-labs/cow-sdk/commit/6f11dfdca4cecee7d036fc2ae49c886832db25bf))
* release main ([#802](https://github.com/substance-labs/cow-sdk/issues/802)) ([5583ca4](https://github.com/substance-labs/cow-sdk/commit/5583ca446f498416565b79485bcaf7708f1ba224))
* release main ([#805](https://github.com/substance-labs/cow-sdk/issues/805)) ([adbc6a9](https://github.com/substance-labs/cow-sdk/commit/adbc6a98eb15b02a87215a1bd446982553219b41))
* release main ([#806](https://github.com/substance-labs/cow-sdk/issues/806)) ([93d805f](https://github.com/substance-labs/cow-sdk/commit/93d805fb93820b8c8ce2e2c2ce7f505243c1bd30))
* release main ([#811](https://github.com/substance-labs/cow-sdk/issues/811)) ([816c990](https://github.com/substance-labs/cow-sdk/commit/816c990e87a39a122c918d6748b2f254350c4be5))
* release main ([#812](https://github.com/substance-labs/cow-sdk/issues/812)) ([4981e10](https://github.com/substance-labs/cow-sdk/commit/4981e1060718f701ad3a6a096e71ef2e544f29fe))
* release main ([#816](https://github.com/substance-labs/cow-sdk/issues/816)) ([aad43b3](https://github.com/substance-labs/cow-sdk/commit/aad43b32d795ad4f7b8d57e1cb06e3dd78458202))
* release main ([#819](https://github.com/substance-labs/cow-sdk/issues/819)) ([5f7ecfb](https://github.com/substance-labs/cow-sdk/commit/5f7ecfba74abc721b80c5fe6f4997f9518c40788))
* release main ([#826](https://github.com/substance-labs/cow-sdk/issues/826)) ([baaa708](https://github.com/substance-labs/cow-sdk/commit/baaa7088ac15b89fb83310e54aa52f09d19132ff))
* release main ([#832](https://github.com/substance-labs/cow-sdk/issues/832)) ([5dafcb8](https://github.com/substance-labs/cow-sdk/commit/5dafcb8ec5593250dba1ff6e9fdbf8eb11d974cf))
* release main ([#836](https://github.com/substance-labs/cow-sdk/issues/836)) ([a7e1af9](https://github.com/substance-labs/cow-sdk/commit/a7e1af993f501e313fb90573148b3d2d42e5168a))
* release main ([#840](https://github.com/substance-labs/cow-sdk/issues/840)) ([1a22c69](https://github.com/substance-labs/cow-sdk/commit/1a22c69592e283bb1a15ece9799a5b6f8c446765))
* release main ([#842](https://github.com/substance-labs/cow-sdk/issues/842)) ([c4c238d](https://github.com/substance-labs/cow-sdk/commit/c4c238d990d2089a66f9d8dc7401cd71b63d394b))
* release main ([#843](https://github.com/substance-labs/cow-sdk/issues/843)) ([7b41c2d](https://github.com/substance-labs/cow-sdk/commit/7b41c2ddcea33a49f519d7c816ad32cf2d6f9757))
* release main ([#848](https://github.com/substance-labs/cow-sdk/issues/848)) ([a56dead](https://github.com/substance-labs/cow-sdk/commit/a56dead934dd2d7d72583d996ea9f61e6091534b))
* release main ([#857](https://github.com/substance-labs/cow-sdk/issues/857)) ([17fcfc5](https://github.com/substance-labs/cow-sdk/commit/17fcfc590be8529dc4fe05b1c472fef1b07b47f4))
* release main ([#861](https://github.com/substance-labs/cow-sdk/issues/861)) ([c178e68](https://github.com/substance-labs/cow-sdk/commit/c178e68beaf46bb33b1ad2ec97212eec62172816))
* release main ([#864](https://github.com/substance-labs/cow-sdk/issues/864)) ([a5207e0](https://github.com/substance-labs/cow-sdk/commit/a5207e0dba212942ecf5564c8d01c9c75c77f647))
* release main ([#866](https://github.com/substance-labs/cow-sdk/issues/866)) ([5c1062c](https://github.com/substance-labs/cow-sdk/commit/5c1062c3111a7653345ee8c978554aec54979965))
* release main ([#880](https://github.com/substance-labs/cow-sdk/issues/880)) ([447b5e1](https://github.com/substance-labs/cow-sdk/commit/447b5e17b36a800a5f6fe6e4f890d2d77d017495))
* release main ([#886](https://github.com/substance-labs/cow-sdk/issues/886)) ([5115efe](https://github.com/substance-labs/cow-sdk/commit/5115efeb6f6f591c5eae653c63c5c5930eb24331))
* release main ([#887](https://github.com/substance-labs/cow-sdk/issues/887)) ([74393ee](https://github.com/substance-labs/cow-sdk/commit/74393ee2923a2932584998169daca6ce3c2da60c))
* release main ([#889](https://github.com/substance-labs/cow-sdk/issues/889)) ([8659102](https://github.com/substance-labs/cow-sdk/commit/865910213586d59f709c8e34726f799503bdfafb))
* release main ([#894](https://github.com/substance-labs/cow-sdk/issues/894)) ([6ca7944](https://github.com/substance-labs/cow-sdk/commit/6ca794476e3411ab5a3774d6cd88804b9f875d29))
* release main ([#900](https://github.com/substance-labs/cow-sdk/issues/900)) ([3fdbda2](https://github.com/substance-labs/cow-sdk/commit/3fdbda2042db284c73e3b16b90961e1c31a475cd))
* revert not published release ([5facf05](https://github.com/substance-labs/cow-sdk/commit/5facf05c67121404b7b5aa1e77950961b06eca81))
* revert release ([#634](https://github.com/substance-labs/cow-sdk/issues/634)) ([fc7bf61](https://github.com/substance-labs/cow-sdk/commit/fc7bf61444619d4b2c3a3dd55b7ce52c197b1878))
* revert release ([#833](https://github.com/substance-labs/cow-sdk/issues/833)) ([0c40a9b](https://github.com/substance-labs/cow-sdk/commit/0c40a9b3ee828c7ede66576f02e1b571e96140cd))
* **sdk-agnostic-lib:** improve scripts and types ([#407](https://github.com/substance-labs/cow-sdk/issues/407)) ([c4b5e08](https://github.com/substance-labs/cow-sdk/commit/c4b5e086ce46086e9430d5f03ed330502349fbf3))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/substance-labs/cow-sdk/issues/354)) ([55d3068](https://github.com/substance-labs/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))
* Update openapi.yml version ([#888](https://github.com/substance-labs/cow-sdk/issues/888)) ([b8a3726](https://github.com/substance-labs/cow-sdk/commit/b8a37263195afba0a12a42c879eb13c1a2cc2e8b))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 1.0.0
    * @cowprotocol/sdk-config bumped to 3.0.0
    * @cowprotocol/sdk-contracts-ts bumped to 4.0.0
    * @cowprotocol/sdk-order-book bumped to 5.0.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 1.0.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 1.0.0
    * @cowprotocol/sdk-viem-adapter bumped to 1.0.0

## [1.1.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.6...sdk-order-signing-v1.1.0) (2026-06-15)


### ✨ Features

* per-package test coverage badges, updated in CI ([#895](https://github.com/cowprotocol/cow-sdk/issues/895)) ([c73246c](https://github.com/cowprotocol/cow-sdk/commit/c73246cc52c4fc79b2628b7c5f580695fd3dc1e2))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.12.0
    * @cowprotocol/sdk-config bumped to 2.3.1
    * @cowprotocol/sdk-contracts-ts bumped to 3.2.0
    * @cowprotocol/sdk-order-book bumped to 4.0.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.10
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.10
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.24

## [1.0.6](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.5...sdk-order-signing-v1.0.6) (2026-06-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.2
    * @cowprotocol/sdk-config bumped to 2.3.0
    * @cowprotocol/sdk-contracts-ts bumped to 3.1.2
    * @cowprotocol/sdk-order-book bumped to 3.2.2
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.9
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.9
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.23

## [1.0.5](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.4...sdk-order-signing-v1.0.5) (2026-06-02)


### 🔧 Miscellaneous

* Update openapi.yml version ([#888](https://github.com/cowprotocol/cow-sdk/issues/888)) ([b8a3726](https://github.com/cowprotocol/cow-sdk/commit/b8a37263195afba0a12a42c879eb13c1a2cc2e8b))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.1
    * @cowprotocol/sdk-config bumped to 2.2.1
    * @cowprotocol/sdk-contracts-ts bumped to 3.1.1
    * @cowprotocol/sdk-order-book bumped to 3.2.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.8
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.8
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.22

## [1.0.4](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.3...sdk-order-signing-v1.0.4) (2026-05-27)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.11.0
    * @cowprotocol/sdk-config bumped to 2.2.0
    * @cowprotocol/sdk-contracts-ts bumped to 3.1.0
    * @cowprotocol/sdk-order-book bumped to 3.2.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.7
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.7
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.21

## [1.0.3](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.2...sdk-order-signing-v1.0.3) (2026-05-22)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.3
    * @cowprotocol/sdk-config bumped to 2.1.0
    * @cowprotocol/sdk-contracts-ts bumped to 3.0.3
    * @cowprotocol/sdk-order-book bumped to 3.1.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.6
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.6
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.20

## [1.0.2](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.1...sdk-order-signing-v1.0.2) (2026-05-20)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 3.0.2
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.5
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.5
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.19

## [1.0.1](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v1.0.0...sdk-order-signing-v1.0.1) (2026-04-20)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 3.0.1

## [1.0.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.3.0...sdk-order-signing-v1.0.0) (2026-04-16)


### ⚠ BREAKING CHANGES

* bring cow.fi back ([#863](https://github.com/cowprotocol/cow-sdk/issues/863))

### ✨ Features

* bring cow.fi back ([#863](https://github.com/cowprotocol/cow-sdk/issues/863)) ([d607fd2](https://github.com/cowprotocol/cow-sdk/commit/d607fd2cfbc93ace39de04f3a7870f723fdd9b21))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.2
    * @cowprotocol/sdk-config bumped to 2.0.0
    * @cowprotocol/sdk-contracts-ts bumped to 3.0.0
    * @cowprotocol/sdk-order-book bumped to 3.0.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.4
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.4
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.18

## [0.3.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.5...sdk-order-signing-v0.3.0) (2026-04-14)


### ✨ Features

* migrate to cow.finance domain ([#860](https://github.com/cowprotocol/cow-sdk/issues/860)) ([a4e7633](https://github.com/cowprotocol/cow-sdk/commit/a4e76333b7a276baec5c977f44b15498550d8e50))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.1
    * @cowprotocol/sdk-config bumped to 1.2.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.5.0
    * @cowprotocol/sdk-order-book bumped to 2.1.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.3
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.3
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.17

## [0.2.5](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.4...sdk-order-signing-v0.2.5) (2026-04-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.10.0
    * @cowprotocol/sdk-config bumped to 1.1.3
    * @cowprotocol/sdk-contracts-ts bumped to 2.4.0
    * @cowprotocol/sdk-order-book bumped to 2.0.5
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.2
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.2
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.16

## [0.2.4](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.3...sdk-order-signing-v0.2.4) (2026-04-01)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.9.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.3.0
    * @cowprotocol/sdk-order-book bumped to 2.0.4
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.1
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.1
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.15

## [0.2.3](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.2...sdk-order-signing-v0.2.3) (2026-03-17)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 2.2.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.4.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.4.0

## [0.2.2](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.1...sdk-order-signing-v0.2.2) (2026-03-17)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.2
    * @cowprotocol/sdk-config bumped to 1.1.2
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.2
    * @cowprotocol/sdk-order-book bumped to 2.0.3
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.14
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.14
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.14

## [0.2.1](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.0...sdk-order-signing-v0.2.1) (2026-03-16)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.1
    * @cowprotocol/sdk-config bumped to 1.1.1
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.1
    * @cowprotocol/sdk-order-book bumped to 2.0.2
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.13
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.13
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.13

## [0.2.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.38...sdk-order-signing-v0.2.0) (2026-03-16)


### ✨ Features

* update settlement and vault relayer contracts on staging ([#807](https://github.com/cowprotocol/cow-sdk/issues/807)) ([0f9a03e](https://github.com/cowprotocol/cow-sdk/commit/0f9a03e6bfa3468630e46735f7583618ae711b73))


### 🔧 Miscellaneous

* release main ([#826](https://github.com/cowprotocol/cow-sdk/issues/826)) ([baaa708](https://github.com/cowprotocol/cow-sdk/commit/baaa7088ac15b89fb83310e54aa52f09d19132ff))
* release main ([#832](https://github.com/cowprotocol/cow-sdk/issues/832)) ([5dafcb8](https://github.com/cowprotocol/cow-sdk/commit/5dafcb8ec5593250dba1ff6e9fdbf8eb11d974cf))
* revert release ([#833](https://github.com/cowprotocol/cow-sdk/issues/833)) ([0c40a9b](https://github.com/cowprotocol/cow-sdk/commit/0c40a9b3ee828c7ede66576f02e1b571e96140cd))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.8.0
    * @cowprotocol/sdk-config bumped to 1.1.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.0
    * @cowprotocol/sdk-order-book bumped to 2.0.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.12
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.12
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.12

## [0.1.38](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.37...sdk-order-signing-v0.1.38) (2026-03-10)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.7.1
    * @cowprotocol/sdk-config bumped to 1.0.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.0.0
    * @cowprotocol/sdk-order-book bumped to 2.0.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.11
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.11
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.11

## [0.1.37](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.36...sdk-order-signing-v0.1.37) (2026-03-10)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-order-book bumped to 1.1.2

## [0.1.36](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.35...sdk-order-signing-v0.1.36) (2026-03-04)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.7.0
    * @cowprotocol/sdk-config bumped to 0.10.0
    * @cowprotocol/sdk-contracts-ts bumped to 1.8.0
    * @cowprotocol/sdk-order-book bumped to 1.1.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.10
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.10
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.10

## [0.1.35](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.34...sdk-order-signing-v0.1.35) (2026-03-04)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.3
    * @cowprotocol/sdk-config bumped to 0.9.0
    * @cowprotocol/sdk-contracts-ts bumped to 1.7.0
    * @cowprotocol/sdk-order-book bumped to 1.1.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.9
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.9
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.9

## [0.1.34](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.33...sdk-order-signing-v0.1.34) (2026-02-26)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-order-book bumped to 1.0.0

## [0.1.33](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.32...sdk-order-signing-v0.1.33) (2026-02-20)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.2
    * @cowprotocol/sdk-config bumped to 0.8.1
    * @cowprotocol/sdk-contracts-ts bumped to 1.6.1
    * @cowprotocol/sdk-order-book bumped to 0.6.6
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.8
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.8
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.8

## [0.1.32](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.31...sdk-order-signing-v0.1.32) (2026-02-18)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.1
    * @cowprotocol/sdk-config bumped to 0.8.0
    * @cowprotocol/sdk-contracts-ts bumped to 1.6.0
    * @cowprotocol/sdk-order-book bumped to 0.6.5
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.7
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.7
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.7

## [0.1.31](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.30...sdk-order-signing-v0.1.31) (2026-02-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.6.0
    * @cowprotocol/sdk-contracts-ts bumped to 1.5.0
    * @cowprotocol/sdk-order-book bumped to 0.6.4
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.6
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.6
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.6

## [0.1.30](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.29...sdk-order-signing-v0.1.30) (2026-02-02)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.4
    * @cowprotocol/sdk-config bumped to 0.7.3
    * @cowprotocol/sdk-contracts-ts bumped to 1.4.2
    * @cowprotocol/sdk-order-book bumped to 0.6.3
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.5
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.5
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.5

## [0.1.29](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.28...sdk-order-signing-v0.1.29) (2026-02-02)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.3
    * @cowprotocol/sdk-config bumped to 0.7.2
    * @cowprotocol/sdk-contracts-ts bumped to 1.4.1
    * @cowprotocol/sdk-order-book bumped to 0.6.2
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.4
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.4
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.4

## [0.1.28](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.27...sdk-order-signing-v0.1.28) (2026-01-28)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.2
    * @cowprotocol/sdk-config bumped to 0.7.1
    * @cowprotocol/sdk-contracts-ts bumped to 1.4.0
    * @cowprotocol/sdk-order-book bumped to 0.6.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.3
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.3
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.3

## [0.1.27](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.26...sdk-order-signing-v0.1.27) (2026-01-28)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.1
    * @cowprotocol/sdk-config bumped to 0.7.0
    * @cowprotocol/sdk-contracts-ts bumped to 1.3.0
    * @cowprotocol/sdk-order-book bumped to 0.6.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.2
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.2
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.2

## [0.1.26](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.25...sdk-order-signing-v0.1.26) (2026-01-22)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 1.2.0

## [0.1.25](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.24...sdk-order-signing-v0.1.25) (2026-01-21)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 1.1.1

## [0.1.24](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.23...sdk-order-signing-v0.1.24) (2026-01-19)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.0
    * @cowprotocol/sdk-config bumped to 0.6.3
    * @cowprotocol/sdk-contracts-ts bumped to 1.1.0
    * @cowprotocol/sdk-order-book bumped to 0.5.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.1
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.1
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.1

## [0.1.23](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.22...sdk-order-signing-v0.1.23) (2025-12-22)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-order-book bumped to 0.5.0

## [0.1.22](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.21...sdk-order-signing-v0.1.22) (2025-12-19)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 1.0.0

## [0.1.21](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.20...sdk-order-signing-v0.1.21) (2025-12-11)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.6.2
    * @cowprotocol/sdk-contracts-ts bumped to 0.8.1
    * @cowprotocol/sdk-order-book bumped to 0.4.4

## [0.1.20](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.19...sdk-order-signing-v0.1.20) (2025-12-10)


### 🔧 Miscellaneous

* release main ([#741](https://github.com/cowprotocol/cow-sdk/issues/741)) ([32fb8bb](https://github.com/cowprotocol/cow-sdk/commit/32fb8bbe6b1172c2666f330d0d50cdc2f7c2554f))
* revert not published release ([5facf05](https://github.com/cowprotocol/cow-sdk/commit/5facf05c67121404b7b5aa1e77950961b06eca81))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.8.0

## [0.1.19](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.18...sdk-order-signing-v0.1.19) (2025-12-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.6.1
    * @cowprotocol/sdk-contracts-ts bumped to 0.7.4
    * @cowprotocol/sdk-order-book bumped to 0.4.3

## [0.1.18](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.17...sdk-order-signing-v0.1.18) (2025-12-04)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.6.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.7.3
    * @cowprotocol/sdk-order-book bumped to 0.4.2

## [0.1.17](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.16...sdk-order-signing-v0.1.17) (2025-12-03)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.5.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.7.2
    * @cowprotocol/sdk-order-book bumped to 0.4.1

## [0.1.16](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.15...sdk-order-signing-v0.1.16) (2025-12-01)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-order-book bumped to 0.4.0

## [0.1.15](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.14...sdk-order-signing-v0.1.15) (2025-11-27)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-order-book bumped to 0.3.2

## [0.1.14](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.13...sdk-order-signing-v0.1.14) (2025-11-27)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.4.1
    * @cowprotocol/sdk-contracts-ts bumped to 0.7.1
    * @cowprotocol/sdk-order-book bumped to 0.3.1

## [0.1.13](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.12...sdk-order-signing-v0.1.13) (2025-11-24)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.7.0

## [0.1.12](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.11...sdk-order-signing-v0.1.12) (2025-11-24)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.4.0
    * @cowprotocol/sdk-config bumped to 0.4.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.6.0
    * @cowprotocol/sdk-order-book bumped to 0.3.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.3.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.3.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.0

## [0.1.11](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.10...sdk-order-signing-v0.1.11) (2025-11-07)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.5.0

## [0.1.10](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.9...sdk-order-signing-v0.1.10) (2025-11-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.3.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.4.4
    * @cowprotocol/sdk-order-book bumped to 0.2.0

## [0.1.9](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.8...sdk-order-signing-v0.1.9) (2025-10-30)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.4.3

## [0.1.8](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.7...sdk-order-signing-v0.1.8) (2025-10-29)


### 🔧 Miscellaneous

* release main ([#620](https://github.com/cowprotocol/cow-sdk/issues/620)) ([b36394a](https://github.com/cowprotocol/cow-sdk/commit/b36394a2ba38957edb47ffc4451ea6624d66737b))
* revert release ([#634](https://github.com/cowprotocol/cow-sdk/issues/634)) ([fc7bf61](https://github.com/cowprotocol/cow-sdk/commit/fc7bf61444619d4b2c3a3dd55b7ce52c197b1878))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.3.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.4.2
    * @cowprotocol/sdk-order-book bumped to 0.1.4
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.2.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.2.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.2.0

## [0.1.7](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.6...sdk-order-signing-v0.1.7) (2025-10-24)


### 🐛 Bug Fixes

* **trading:** add EIP1271 signature support ([#584](https://github.com/cowprotocol/cow-sdk/issues/584)) ([ca9e834](https://github.com/cowprotocol/cow-sdk/commit/ca9e834e2b0edf8a757e01383b2218d5ecfbe25e))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.2
    * @cowprotocol/sdk-config bumped to 0.2.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.4.1
    * @cowprotocol/sdk-order-book bumped to 0.1.3
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.1.3
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.1.3
    * @cowprotocol/sdk-viem-adapter bumped to 0.1.3

## [0.1.6](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.5...sdk-order-signing-v0.1.6) (2025-10-15)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.4.0

## [0.1.5](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.4...sdk-order-signing-v0.1.5) (2025-10-08)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.1
    * @cowprotocol/sdk-contracts-ts bumped to 0.3.1
    * @cowprotocol/sdk-order-book bumped to 0.1.2
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.1.2
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.1.2
    * @cowprotocol/sdk-viem-adapter bumped to 0.1.2

## [0.1.4](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.3...sdk-order-signing-v0.1.4) (2025-10-06)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.2.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.3.0
    * @cowprotocol/sdk-order-book bumped to 0.1.1
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.1.1
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.1.1
    * @cowprotocol/sdk-viem-adapter bumped to 0.1.1

## [0.1.3](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.2...sdk-order-signing-v0.1.3) (2025-09-24)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.2.1

## [0.1.2](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.1...sdk-order-signing-v0.1.2) (2025-09-23)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.2.0

## [0.1.1](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.0...sdk-order-signing-v0.1.1) (2025-09-22)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 0.1.1

## [0.1.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.8-beta.0...sdk-order-signing-v0.1.0) (2025-09-17)


### ⚠ BREAKING CHANGES

* release cow-sdk v7

### ✨ Features

* release cow-sdk v7 ([6cd3e57](https://github.com/cowprotocol/cow-sdk/commit/6cd3e573687b1ffdbc0fdcb8cdbb414d88546e38))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.1.0
    * @cowprotocol/sdk-config bumped to 0.1.0
    * @cowprotocol/sdk-contracts-ts bumped to 0.1.0
    * @cowprotocol/sdk-order-book bumped to 0.1.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.1.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.1.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.1.0

## [0.2.8-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.7-beta.0...sdk-order-signing-v0.2.8-beta.0) (2025-09-17)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.5.0-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.3.0-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.3.1-beta.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.2.5-beta.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.2.5-beta.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.1-beta.0

## [0.2.7-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.6-beta.0...sdk-order-signing-v0.2.7-beta.0) (2025-09-16)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 2.2.1-beta.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.2.4-beta.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.2.4-beta.0

## [0.2.6-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.5-beta.0...sdk-order-signing-v0.2.6-beta.0) (2025-09-16)


### 📚 Documentation

* update README to focus on main use cases ([#493](https://github.com/cowprotocol/cow-sdk/issues/493)) ([a05cb1b](https://github.com/cowprotocol/cow-sdk/commit/a05cb1ba11b5f9895d7cfe6262cf74c4089fd73c))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.4.0-beta.0
    * @cowprotocol/sdk-config bumped to 0.3.3-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.2.0-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.3.0-beta.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.2.3-beta.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.2.3-beta.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.3.0-beta.0

## [0.2.5-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.4-beta.0...sdk-order-signing-v0.2.5-beta.0) (2025-09-15)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.3.2-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.7-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.2.4-beta.0

## [0.2.4-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.3-beta.0...sdk-order-signing-v0.2.4-beta.0) (2025-09-15)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.3.1-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.6-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.2.3-beta.0

## [0.2.3-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.2-beta.0...sdk-order-signing-v0.2.3-beta.0) (2025-09-15)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.5-beta.0

## [0.2.2-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.1-beta.0...sdk-order-signing-v0.2.2-beta.0) (2025-09-11)


### 🔧 Miscellaneous

* release main ([#488](https://github.com/cowprotocol/cow-sdk/issues/488)) ([6344fa6](https://github.com/cowprotocol/cow-sdk/commit/6344fa619465e6f94637677823a18646f06fa7c9))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-common bumped to 0.3.0-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.4-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.2.2-beta.0
  * devDependencies
    * @cowprotocol/sdk-ethers-v5-adapter bumped to 0.2.2-beta.0
    * @cowprotocol/sdk-ethers-v6-adapter bumped to 0.2.2-beta.0
    * @cowprotocol/sdk-viem-adapter bumped to 0.2.2-beta.0

## [0.2.1-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.2.0-beta.0...sdk-order-signing-v0.2.1-beta.0) (2025-09-11)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @cowprotocol/sdk-config bumped to 0.3.0-beta.0
    * @cowprotocol/sdk-contracts-ts bumped to 2.1.3-beta.0
    * @cowprotocol/sdk-order-book bumped to 0.2.1-beta.0

## [0.2.0-beta.0](https://github.com/cowprotocol/cow-sdk/compare/sdk-order-signing-v0.1.0-beta.0...sdk-order-signing-v0.2.0-beta.0) (2025-08-28)


### ✨ Features

* allow changing backoff and limiter per request ([#208](https://github.com/cowprotocol/cow-sdk/issues/208)) ([ebea5ca](https://github.com/cowprotocol/cow-sdk/commit/ebea5ca0858aeb89ae3e5d5407c8903c3ca5178d))
* move order-signing to new package ([c60daab](https://github.com/cowprotocol/cow-sdk/commit/c60daabcd3e9311913f27b519561b7b992958cf4))
* refactor order-signing ([8e28d1b](https://github.com/cowprotocol/cow-sdk/commit/8e28d1bdbda9632347cacaae906298e736f4a7b3))
* refactor order-signing tests ([2d99282](https://github.com/cowprotocol/cow-sdk/commit/2d99282382da1545cd205cf246db0f055e7e0415))
* **sdk-agnostic-lib:** create cow trading package ([#368](https://github.com/cowprotocol/cow-sdk/issues/368)) ([0a4534a](https://github.com/cowprotocol/cow-sdk/commit/0a4534aababce4f5d8bab991cd6ae9f51842d719))
* **sdk-agnostic-lib:** Create weiroll package ([#371](https://github.com/cowprotocol/cow-sdk/issues/371)) ([8f6a2e1](https://github.com/cowprotocol/cow-sdk/commit/8f6a2e16e5e7a43a5afc43cf5faab174be916b2e))
* simplify OrderSigningUtils to use static methods only ([#417](https://github.com/cowprotocol/cow-sdk/issues/417)) ([899ca43](https://github.com/cowprotocol/cow-sdk/commit/899ca4325be831b6711468d1df3733d98fe913b0))


### 🐛 Bug Fixes

* **lib-agnostic:** add setProvider() method to adapters ([#432](https://github.com/cowprotocol/cow-sdk/issues/432)) ([64c0ea9](https://github.com/cowprotocol/cow-sdk/commit/64c0ea94d802aa167b978ae0859353d801de0911))


### 🔧 Miscellaneous

* **sdk-agnostic-lib:** improve scripts and types ([#407](https://github.com/cowprotocol/cow-sdk/issues/407)) ([c4b5e08](https://github.com/cowprotocol/cow-sdk/commit/c4b5e086ce46086e9430d5f03ed330502349fbf3))
* **sdk-agnostic-lib:** merge multiple PRs to avoid conflicts and speed up base branch sync ([#354](https://github.com/cowprotocol/cow-sdk/issues/354)) ([55d3068](https://github.com/cowprotocol/cow-sdk/commit/55d3068c52217dd2618d8c180ab4fed8c9334c72))
