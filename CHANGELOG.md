# Changelog

## 0.2.1 (2025-05-22)

Full Changelog: [v0.2.0...v0.2.1](https://github.com/VeritasLabsInc/veritas-api-python/compare/v0.2.0...v0.2.1)

### Bug Fixes

* **package:** support direct resource imports ([627ce75](https://github.com/VeritasLabsInc/veritas-api-python/commit/627ce75456db8f630babb3d583a2516e496588bc))
* **perf:** optimize some hot paths ([c58c347](https://github.com/VeritasLabsInc/veritas-api-python/commit/c58c347ece62e2a636a7cbcd2ffcfade9cc71284))
* **perf:** skip traversing types for NotGiven values ([0d724ae](https://github.com/VeritasLabsInc/veritas-api-python/commit/0d724aec024e6c269f9a619e838c4b80c40fe86d))
* **pydantic v1:** more robust ModelField.annotation check ([6b99a11](https://github.com/VeritasLabsInc/veritas-api-python/commit/6b99a11a91dee4b75274422c1cef994219ffdac3))


### Chores

* broadly detect json family of content-type headers ([f05dbb3](https://github.com/VeritasLabsInc/veritas-api-python/commit/f05dbb3460f5659e6e95f164f18bb80f83f649c1))
* **ci:** add timeout thresholds for CI jobs ([ed1691a](https://github.com/VeritasLabsInc/veritas-api-python/commit/ed1691a264a69bde9056a47afd7b874950c82f65))
* **ci:** fix installation instructions ([ed6d9bf](https://github.com/VeritasLabsInc/veritas-api-python/commit/ed6d9bfaa4026996b81199fcac1a0e44aeb8a658))
* **ci:** only use depot for staging repos ([fd8052c](https://github.com/VeritasLabsInc/veritas-api-python/commit/fd8052c6d44efbbd8e84857ba4b6a6edea95d48c))
* **ci:** upload sdks to package manager ([3de1e62](https://github.com/VeritasLabsInc/veritas-api-python/commit/3de1e626e39b6db1fd2b1694cfad64bc3558dea0))
* **client:** minor internal fixes ([22e1b45](https://github.com/VeritasLabsInc/veritas-api-python/commit/22e1b459fb963ffd26588faae20fa17f34ee1820))
* **docs:** grammar improvements ([deedc8c](https://github.com/VeritasLabsInc/veritas-api-python/commit/deedc8ccc34ba74d9fdd41813833e9a871646898))
* **internal:** avoid errors for isinstance checks on proxies ([954049c](https://github.com/VeritasLabsInc/veritas-api-python/commit/954049c044a7c513fd647e877254bf7a6c85e0b6))
* **internal:** base client updates ([64f9abb](https://github.com/VeritasLabsInc/veritas-api-python/commit/64f9abb217883d3cdf769a563d47aca02858078b))
* **internal:** bump pyright version ([3299bde](https://github.com/VeritasLabsInc/veritas-api-python/commit/3299bde09687ac7d652f43506f356a9499d68a08))
* **internal:** codegen related update ([c2709b6](https://github.com/VeritasLabsInc/veritas-api-python/commit/c2709b637e0e6d7fce62112895a7d48b10c8a1d4))
* **internal:** expand CI branch coverage ([9c6b409](https://github.com/VeritasLabsInc/veritas-api-python/commit/9c6b40970b0462e47ff89a6a4cdc4047ea0a82c4))
* **internal:** fix list file params ([9f54679](https://github.com/VeritasLabsInc/veritas-api-python/commit/9f5467901d026309cfd3d65a1e426cecb7222c3c))
* **internal:** import reformatting ([29f00c5](https://github.com/VeritasLabsInc/veritas-api-python/commit/29f00c502366ae1a9d4783f8a6c7f9c3e149d34e))
* **internal:** reduce CI branch coverage ([4350709](https://github.com/VeritasLabsInc/veritas-api-python/commit/4350709e2107d0492bd71b217c3566358464ff26))
* **internal:** refactor retries to not use recursion ([e276091](https://github.com/VeritasLabsInc/veritas-api-python/commit/e276091bdec99880ad750deca3c0476f39334f65))
* **internal:** remove trailing character ([#14](https://github.com/VeritasLabsInc/veritas-api-python/issues/14)) ([430e694](https://github.com/VeritasLabsInc/veritas-api-python/commit/430e69404c58fde36d324227826cb36ca081ca39))
* **internal:** slight transform perf improvement ([#16](https://github.com/VeritasLabsInc/veritas-api-python/issues/16)) ([398042d](https://github.com/VeritasLabsInc/veritas-api-python/commit/398042d8c06ae5e5300ac47b7ccb409eb431c655))
* **internal:** update models test ([39e9892](https://github.com/VeritasLabsInc/veritas-api-python/commit/39e98926f2c54b2333fd43e75b03e7aade7a1aa1))
* **internal:** update pyright settings ([9342ad2](https://github.com/VeritasLabsInc/veritas-api-python/commit/9342ad263a457fe209fc58a6c114e4a0670d1e73))


### Documentation

* remove or fix invalid readme examples ([910f1be](https://github.com/VeritasLabsInc/veritas-api-python/commit/910f1be52d8aa5df34f63b576996b62e38486422))

## 0.2.0 (2025-03-27)

Full Changelog: [v0.1.0...v0.2.0](https://github.com/VeritasLabsInc/veritas-api-python/compare/v0.1.0...v0.2.0)

### Features

* **api:** manual updates ([#10](https://github.com/VeritasLabsInc/veritas-api-python/issues/10)) ([2be9090](https://github.com/VeritasLabsInc/veritas-api-python/commit/2be909076799043280d3c91cf9031890dcdaf0e9))


### Chores

* fix typos ([#12](https://github.com/VeritasLabsInc/veritas-api-python/issues/12)) ([45e6fd1](https://github.com/VeritasLabsInc/veritas-api-python/commit/45e6fd1ad8afb99df24857792d9d433197931d35))

## 0.1.0 (2025-03-19)

Full Changelog: [v0.0.1-alpha.1...v0.1.0](https://github.com/VeritasLabsInc/veritas-api-python/compare/v0.0.1-alpha.1...v0.1.0)

### Features

* **api:** api update ([#5](https://github.com/VeritasLabsInc/veritas-api-python/issues/5)) ([3e068d2](https://github.com/VeritasLabsInc/veritas-api-python/commit/3e068d2e8f12b5f6e219c5cf4ad58f35bc9341d9))
* **api:** manual updates ([#7](https://github.com/VeritasLabsInc/veritas-api-python/issues/7)) ([9ce3f9e](https://github.com/VeritasLabsInc/veritas-api-python/commit/9ce3f9e1cae80a8d621727ddbeec3a0a141c9f40))
* **api:** manual updates ([#8](https://github.com/VeritasLabsInc/veritas-api-python/issues/8)) ([449579a](https://github.com/VeritasLabsInc/veritas-api-python/commit/449579a5f0451ec6f49fc1aef4772693cf187f7e))

## 0.0.1-alpha.1 (2025-03-18)

Full Changelog: [v0.0.1-alpha.0...v0.0.1-alpha.1](https://github.com/VeritasLabsInc/veritas-api-python/compare/v0.0.1-alpha.0...v0.0.1-alpha.1)

### Chores

* go live ([#1](https://github.com/VeritasLabsInc/veritas-api-python/issues/1)) ([9b545b6](https://github.com/VeritasLabsInc/veritas-api-python/commit/9b545b6bf8b9bfe74a2217a9d0c6c683857b2429))
* update SDK settings ([#3](https://github.com/VeritasLabsInc/veritas-api-python/issues/3)) ([75c001f](https://github.com/VeritasLabsInc/veritas-api-python/commit/75c001f469dc0136dc5a2bb2dc101cdf5450891f))
