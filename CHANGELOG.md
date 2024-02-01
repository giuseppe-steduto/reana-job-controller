# Changelog

## [0.9.3](https://github.com/giuseppe-steduto/reana-job-controller/compare/v0.9.2...0.9.3) (2024-02-01)


### Build

* **docker:** non-editable submodules in "latest" mode ([#416](https://github.com/giuseppe-steduto/reana-job-controller/issues/416)) ([3bdda63](https://github.com/giuseppe-steduto/reana-job-controller/commit/3bdda6367d9a4682028a2a7df7268e4c9b42ef6c))


### Features

* **shutdown:** stop all running jobs before stopping workflow ([#423](https://github.com/giuseppe-steduto/reana-job-controller/issues/423)) ([866675b](https://github.com/giuseppe-steduto/reana-job-controller/commit/866675b7288e840130cfee851f4a248a9ae2617d))


### Code refactoring

* **db:** set job status also in the main database ([#423](https://github.com/giuseppe-steduto/reana-job-controller/issues/423)) ([9d6fc99](https://github.com/giuseppe-steduto/reana-job-controller/commit/9d6fc99063deb468fe9d45d9ad626c745c7bd827))
* **monitor:** centralise logs and status updates ([#423](https://github.com/giuseppe-steduto/reana-job-controller/issues/423)) ([3685b01](https://github.com/giuseppe-steduto/reana-job-controller/commit/3685b01a57e1d0b1bd363534ff331b988e04719e))
* **monitor:** move fetching of logs to job-manager ([#423](https://github.com/giuseppe-steduto/reana-job-controller/issues/423)) ([1fc117e](https://github.com/giuseppe-steduto/reana-job-controller/commit/1fc117ebb3dd908a01ee3fd539fa24a07cdb4d16))


### Code style

* **black:** format with black v24 ([#426](https://github.com/giuseppe-steduto/reana-job-controller/issues/426)) ([8a2757e](https://github.com/giuseppe-steduto/reana-job-controller/commit/8a2757ee8bf52d1d5189f1dd1d690cb8922599cb))


### Test suite

* adding stop k8s job test ([8ca36bd](https://github.com/giuseppe-steduto/reana-job-controller/commit/8ca36bd5bde461e6f85cf0a78f9588eba259047b))
* adds requirements_dev for Travis ([6c8adc0](https://github.com/giuseppe-steduto/reana-job-controller/commit/6c8adc0d02b2852dbf79e1e82324c67c92d793f0))


### Continuous integration

* add hadolint and flake8 linters ([4ad0ede](https://github.com/giuseppe-steduto/reana-job-controller/commit/4ad0eded2da54fd92f9da7b4ac03fb6861cb1e06))
* added github actions workflow ([67ea0ed](https://github.com/giuseppe-steduto/reana-job-controller/commit/67ea0ed5c533c9a04213d8dc31a9421db69dc804))
* **commitlint:** addition of commit message linter ([#417](https://github.com/giuseppe-steduto/reana-job-controller/issues/417)) ([f547d3b](https://github.com/giuseppe-steduto/reana-job-controller/commit/f547d3bc25f438203252ea149cf6c6e5d2428189))
* pin hadolint version ([8be1f3d](https://github.com/giuseppe-steduto/reana-job-controller/commit/8be1f3d978c258c1cfa615e59192d99e37bed306))
* publish docker image after new release ([6a2abcb](https://github.com/giuseppe-steduto/reana-job-controller/commit/6a2abcbb90920786ab87496a037eab50a17a85a9))
* **release-please:** initial configuration ([#417](https://github.com/giuseppe-steduto/reana-job-controller/issues/417)) ([fca6f74](https://github.com/giuseppe-steduto/reana-job-controller/commit/fca6f74aa0d0e55e41d96b0e79c66a5cb3517189))
* **release-please:** update version in Dockerfile/OpenAPI specs ([#421](https://github.com/giuseppe-steduto/reana-job-controller/issues/421)) ([e6742f2](https://github.com/giuseppe-steduto/reana-job-controller/commit/e6742f2911df46dfbef3b7e9104330d58e2b4211))
* remove older versions from python tests ([5ee2872](https://github.com/giuseppe-steduto/reana-job-controller/commit/5ee287219aca0bae00ad600bbd29dc2ac4bb04dc))
* update all actions ([2f3ede1](https://github.com/giuseppe-steduto/reana-job-controller/commit/2f3ede1cf130b9b68f71c1c2ec740e8f040dcbf0))


### Documentation

* add .readthedocs.yaml to migrate to RTD v2 ([71fca96](https://github.com/giuseppe-steduto/reana-job-controller/commit/71fca9648faf098a6fdd79d1534e0f973e1fa6a0))
* addition of REST API documentation ([870668f](https://github.com/giuseppe-steduto/reana-job-controller/commit/870668f2def8c574b7d7a5d294d09b58a921969e))
* addition of Travis/Coveralls/RFTD/Waffle/Travis/License badges ([b31c9d8](https://github.com/giuseppe-steduto/reana-job-controller/commit/b31c9d811bc9d532571c7d131ed9ed02d02196ad))
* author ORCID links ([3c1d224](https://github.com/giuseppe-steduto/reana-job-controller/commit/3c1d224fda215ffc7fcacc75fa56af0a26e89276))
* autodoc_mock_imports for gssapi ([2fa5221](https://github.com/giuseppe-steduto/reana-job-controller/commit/2fa52212fb744cec197a2c116da96cdb406c6645)), closes [#274](https://github.com/giuseppe-steduto/reana-job-controller/issues/274)
* better navigation and synced descriptions ([18b942f](https://github.com/giuseppe-steduto/reana-job-controller/commit/18b942fc97a9bb3ef94e2c7f2c438fb1699ae10a))
* better structure ([eada161](https://github.com/giuseppe-steduto/reana-job-controller/commit/eada1613742e92cdd4e2e09febbacf9120caef2a))
* change docs to comply with the new secrets cli format ([ac2292c](https://github.com/giuseppe-steduto/reana-job-controller/commit/ac2292c06b3682cd539a4ea212ab5f13082b3ead))
* fix "fork me on GitHub" ribbon ([d9c4532](https://github.com/giuseppe-steduto/reana-job-controller/commit/d9c4532d61067df0447d18b0cce7b33f466ed976))
* fix ReadTheDocs build ([9c0e67a](https://github.com/giuseppe-steduto/reana-job-controller/commit/9c0e67a11d5efe01263c2dab2270a5a5843d3319))
* fix rtfd build badge so it shows the real status ([07e403b](https://github.com/giuseppe-steduto/reana-job-controller/commit/07e403b5b82494f8c9e9772faa132a8a5ba63fd1))
* HTCondorCERN backend usage ([5d5d6cb](https://github.com/giuseppe-steduto/reana-job-controller/commit/5d5d6cbbca838f32b2d81d4da612c332c6deebad))
* improve documentation ([76ea1f3](https://github.com/giuseppe-steduto/reana-job-controller/commit/76ea1f3d268b678d1ad425088a5cb0749f95b8c0))
* improve sphinxcontrib-openapi rendering ([903830d](https://github.com/giuseppe-steduto/reana-job-controller/commit/903830dd67bcf59797f099c38955df277d3c7384))
* initial release ([930b7bd](https://github.com/giuseppe-steduto/reana-job-controller/commit/930b7bd2fbf0feed4ff2f464e01e51143d5fec8c))
* more copyright header messages ([53546a2](https://github.com/giuseppe-steduto/reana-job-controller/commit/53546a24fa0c8430e4bd108b8c4fc67055399259))
* more structured chapters ([f901df9](https://github.com/giuseppe-steduto/reana-job-controller/commit/f901df93d1254dfbb1bf806b4468c6b4b0f2bd73))
* new logo, panel verbiage and links ([347f218](https://github.com/giuseppe-steduto/reana-job-controller/commit/347f218a64a9971b6c121cf41af3bc76a304d3c3))
* pin sphinx to avoid build failure ([9d94384](https://github.com/giuseppe-steduto/reana-job-controller/commit/9d943844ce7d643748594d23a98a5a4f49dafed0))
* ReadTheDocs configuration ([3c073e4](https://github.com/giuseppe-steduto/reana-job-controller/commit/3c073e4c25dcd70a603a8e47bf73df33121801a4))
* remove reference to unused pykube ([2398903](https://github.com/giuseppe-steduto/reana-job-controller/commit/23989030657d0bb6a419be110624d0964c49c3ca))
* set default language to English ([a57cd83](https://github.com/giuseppe-steduto/reana-job-controller/commit/a57cd83a219200fd766f96c07e0ef98dd18df865))
* single-page RTFD outline ([1cb473b](https://github.com/giuseppe-steduto/reana-job-controller/commit/1cb473b5c714fa9b6825299d1a933dbfb22cc6b6))
* update changelog ([5ac0d25](https://github.com/giuseppe-steduto/reana-job-controller/commit/5ac0d25ee128db8bbd51fe74f01ebfa11620a34e))
* updating job manager class diagram ([9326218](https://github.com/giuseppe-steduto/reana-job-controller/commit/932621811e0d16e85040288716826929872354cc))
