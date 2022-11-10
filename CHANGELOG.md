# Changelog

## 1.0.0 (2022-11-10)


### Features

* Add isDirectoryIgnored; deprecated isIgnored ([7da4290](https://github.com/renawolford6/config-array-repo/commit/7da4290a7dd1201504349807f7202f8e7f340eea))
* Add isExplicitMatch() method ([d50ee64](https://github.com/renawolford6/config-array-repo/commit/d50ee64ed6eefca547942848433d7a07dfca520b))
* Add isIgnored() method ([c016e0a](https://github.com/renawolford6/config-array-repo/commit/c016e0a294faaa751f9cd85dc0f029240c8b0624))
* Add the normalizeSync() method ([6de6e6d](https://github.com/renawolford6/config-array-repo/commit/6de6e6d7e3b6b428e42c018615ccabcc0ef12186))
* Allow async config functions ([593b29d](https://github.com/renawolford6/config-array-repo/commit/593b29dd36d3f23091808911963e4d2ab2f865f1))
* getConfig() now returns undefined when no configs match. ([39aee15](https://github.com/renawolford6/config-array-repo/commit/39aee155d47ae080a550322ad5e5d32fd4bbdd0f))
* Only object configs by default ([1064167](https://github.com/renawolford6/config-array-repo/commit/10641679642e1875c5a420e29b90d9816a675d28))


### Bug Fixes

* Cache negated patterns separately ([ae2721a](https://github.com/renawolford6/config-array-repo/commit/ae2721a02d2fac9d0b8e71474336d18269b1107c))
* **deps:** Update minimatch to secure version ([3ef0609](https://github.com/renawolford6/config-array-repo/commit/3ef06090858e9e538a07913c6a51a61fa859e613))
* Ensure directories can be unignored. ([572c290](https://github.com/renawolford6/config-array-repo/commit/572c290d8b3e7584de2983a6983e590c4dd40246))
* Ensure dot directories are matched correctly ([da5c7b8](https://github.com/renawolford6/config-array-repo/commit/da5c7b8a391e83389b6ae89884a2dde82760beaa))
* Ensure global ignores are honored ([c016e0a](https://github.com/renawolford6/config-array-repo/commit/c016e0a294faaa751f9cd85dc0f029240c8b0624))
* Ensure preprocess method has correct 'this' value. ([c93c3fb](https://github.com/renawolford6/config-array-repo/commit/c93c3fb3cf62440e1605261d8b619d897d697355))
* Ensure subdirectories of ignored directories are ignored ([a1413b0](https://github.com/renawolford6/config-array-repo/commit/a1413b0f49fd0704f4b35c4b0a092fdb2ac4d86d))
* Error conditions for isDirectoryIgnored ([67526f2](https://github.com/renawolford6/config-array-repo/commit/67526f297f17483be6110f16e267570922abf9e9))
* Explicit matching is required against files field ([fc880a8](https://github.com/renawolford6/config-array-repo/commit/fc880a84ccd077720f9e7665bc22438b640120f6))
* Files outside of basePath should be ignored ([d11ff77](https://github.com/renawolford6/config-array-repo/commit/d11ff77d4103b1a876bfbb2df0c6a01cf8607e59))
* files property to not return negated patterns ([411cb77](https://github.com/renawolford6/config-array-repo/commit/411cb77559d125391ec9091330b4709558c379da))
* Global ignores only when no other keys ([a4a6ee3](https://github.com/renawolford6/config-array-repo/commit/a4a6ee3afbfb4d36ea0fe0c7b3b84e701a418056))
* Improve caching to improve performance ([#50](https://github.com/renawolford6/config-array-repo/issues/50)) ([e6b24b9](https://github.com/renawolford6/config-array-repo/commit/e6b24b9a68f68d7cac03bf8eb458675587bb6afe))
* Incorrect behavior of files property with AND patterns ([77025d5](https://github.com/renawolford6/config-array-repo/commit/77025d5de6ce0f8a1ba0c49a5166462aac3c2c92))
* isDirectoryIgnored should match on relative path. ([94b1c92](https://github.com/renawolford6/config-array-repo/commit/94b1c92d1aec335d295d84e1d2728c71f47820fa))
* isDirectoryIgnored should not test negated patterns ([c5c615c](https://github.com/renawolford6/config-array-repo/commit/c5c615c6faa379611dce0b1ccaae8bd8714dde13))
* isFileIgnored should call isDirectoryIgnored ([ee99451](https://github.com/renawolford6/config-array-repo/commit/ee99451f93c0818eed23791a74258dfa9351a74a))
* Make negated ignore patterns work like gitignore ([90d9d26](https://github.com/renawolford6/config-array-repo/commit/90d9d26c6feed15b4dbe23e8388a6f5ede6a8a44))
* Negated patterns to work when files match ([7cf721c](https://github.com/renawolford6/config-array-repo/commit/7cf721c578174a32ff07a3e36ce44848289c5565))
* Object merging error by upgrading object-schema ([b528b47](https://github.com/renawolford6/config-array-repo/commit/b528b4778622c65bd33240322c6722761bc971db))
* Only apply universal patterns if others match. ([1d129b0](https://github.com/renawolford6/config-array-repo/commit/1d129b02022c92f97d47e386185fd868ca7a0973))
* preprocessConfig should have correct 'this' value ([3f282d7](https://github.com/renawolford6/config-array-repo/commit/3f282d72d07960859cdca19842b7cd9451550d8c))
* Properly build package for release ([b970c33](https://github.com/renawolford6/config-array-repo/commit/b970c330018d2c6d4d627a8afb24f0a8eee1a57f))
* Re-introduce ignores fixes ([c760696](https://github.com/renawolford6/config-array-repo/commit/c7606968878ad0a088499e08901944b14b94fe60))
* Throw error if files key isn't a non-empty array ([8a63f02](https://github.com/renawolford6/config-array-repo/commit/8a63f02cd0f1ebc870a55d384bfc088890ef5b3b))
* Unignoring of directories should work ([a584d8b](https://github.com/renawolford6/config-array-repo/commit/a584d8b9b32f51db0d4e3824ae30ff2df5e574b3))


### Performance Improvements

* Cache isDirectoryIgnored calls ([18cbdd6](https://github.com/renawolford6/config-array-repo/commit/18cbdd6190801c394622ee0dbe4af36644b5a9c7))
* Cache Minimatch instances ([f67ab0e](https://github.com/renawolford6/config-array-repo/commit/f67ab0e8ac3eacb29941a3642d426ed1004fdaa6))

## [0.11.7](https://github.com/humanwhocodes/config-array/compare/v0.11.6...v0.11.7) (2022-10-28)


### Bug Fixes

* **deps:** Update minimatch to secure version ([3219294](https://github.com/humanwhocodes/config-array/commit/3219294bf9170c500ee9e212b59e17ef205b7c3c))

## [0.11.6](https://github.com/humanwhocodes/config-array/compare/v0.11.5...v0.11.6) (2022-10-21)


### Bug Fixes

* Only apply universal patterns if others match. ([e69c8fd](https://github.com/humanwhocodes/config-array/commit/e69c8fdbb7696b406821bc723b86b4c5304c4260))

## [0.11.5](https://github.com/humanwhocodes/config-array/compare/v0.11.4...v0.11.5) (2022-10-17)


### Bug Fixes

* Unignoring of directories should work ([e1c9dcd](https://github.com/humanwhocodes/config-array/commit/e1c9dcd05534619effe258596191ea9dc5bb37af))

## [0.11.4](https://github.com/humanwhocodes/config-array/compare/v0.11.3...v0.11.4) (2022-10-14)


### Bug Fixes

* Ensure subdirectories of ignored directories are ignored ([0df450e](https://github.com/humanwhocodes/config-array/commit/0df450eabeb595ae22fe680ce3320dc47edb1e66))

## [0.11.3](https://github.com/humanwhocodes/config-array/compare/v0.11.2...v0.11.3) (2022-10-13)


### Bug Fixes

* Ensure directories can be unignored. ([206404c](https://github.com/humanwhocodes/config-array/commit/206404c490d354a4f39ef9b4a6d0ceaec119abc5))

## [0.11.2](https://github.com/humanwhocodes/config-array/compare/v0.11.1...v0.11.2) (2022-10-03)


### Bug Fixes

* Error conditions for isDirectoryIgnored ([0bd81f5](https://github.com/humanwhocodes/config-array/commit/0bd81f53b7c217d561f70709057c7d77f17e8c6d))
* isDirectoryIgnored should match on relative path. ([3d1eaf6](https://github.com/humanwhocodes/config-array/commit/3d1eaf6389056215e27793cde9c2954c01c78df8))
* isFileIgnored should call isDirectoryIgnored ([270d359](https://github.com/humanwhocodes/config-array/commit/270d359295f376edb0c73905f62a848284d34053))


### Performance Improvements

* Cache isDirectoryIgnored calls ([c5e6720](https://github.com/humanwhocodes/config-array/commit/c5e67208618e253c08bd320efeae4b1f63641e63))

## [0.11.1](https://github.com/humanwhocodes/config-array/compare/v0.11.0...v0.11.1) (2022-09-30)


### Bug Fixes

* isDirectoryIgnored should not test negated patterns ([f6cdb68](https://github.com/humanwhocodes/config-array/commit/f6cdb688784901970fda72eb688eb1a00c44b09a))

## [0.11.0](https://github.com/humanwhocodes/config-array/compare/v0.10.7...v0.11.0) (2022-09-30)


### Features

* Add isDirectoryIgnored; deprecated isIgnored ([e6942f2](https://github.com/humanwhocodes/config-array/commit/e6942f2ce075007d39f23530593b7adb19178a52))

## [0.10.7](https://github.com/humanwhocodes/config-array/compare/v0.10.6...v0.10.7) (2022-09-29)


### Bug Fixes

* Cache negated patterns separately ([fef617b](https://github.com/humanwhocodes/config-array/commit/fef617b6999f9a4b5871d4525c82c4181bc96fb7))

## [0.10.6](https://github.com/humanwhocodes/config-array/compare/v0.10.5...v0.10.6) (2022-09-28)


### Performance Improvements

* Cache Minimatch instances ([5cf9af7](https://github.com/humanwhocodes/config-array/commit/5cf9af7ecaf227d2106be0cebd92d7f5148867e6))

## [0.10.5](https://github.com/humanwhocodes/config-array/compare/v0.10.4...v0.10.5) (2022-09-21)


### Bug Fixes

* Improve caching to improve performance ([#50](https://github.com/humanwhocodes/config-array/issues/50)) ([8a7e8ab](https://github.com/humanwhocodes/config-array/commit/8a7e8ab499bcbb10d7cbdd676197fc686966a64e))

### [0.10.4](https://www.github.com/humanwhocodes/config-array/compare/v0.10.3...v0.10.4) (2022-07-29)


### Bug Fixes

* Global ignores only when no other keys ([1f6b6ae](https://www.github.com/humanwhocodes/config-array/commit/1f6b6ae89152c1ebe118f55e7ea05c37e7c960dc))
* Re-introduce ignores fixes ([b3ec560](https://www.github.com/humanwhocodes/config-array/commit/b3ec560c485bec2f7420fd63a939448b49a073e3))

### [0.10.3](https://www.github.com/humanwhocodes/config-array/compare/v0.10.2...v0.10.3) (2022-07-20)


### Bug Fixes

* Ensure preprocess method has correct 'this' value. ([f86933a](https://www.github.com/humanwhocodes/config-array/commit/f86933a072e5a4069bab2c1ce284dedf0efa715d))

### [0.10.2](https://www.github.com/humanwhocodes/config-array/compare/v0.10.1...v0.10.2) (2022-03-18)


### Bug Fixes

* Files outside of basePath should be ignored ([fc4d7b2](https://www.github.com/humanwhocodes/config-array/commit/fc4d7b2e851959ab9ab84305f6c78c52e9cc2c3c))

### [0.10.1](https://www.github.com/humanwhocodes/config-array/compare/v0.10.0...v0.10.1) (2022-03-03)


### Bug Fixes

* Explicit matching is required against files field ([ab4e428](https://www.github.com/humanwhocodes/config-array/commit/ab4e4282ecea994ef88d273dc47aa24bf3c6972e))

## [0.10.0](https://www.github.com/humanwhocodes/config-array/compare/v0.9.5...v0.10.0) (2022-03-01)


### Features

* Add isExplicitMatch() method ([9ecd90e](https://www.github.com/humanwhocodes/config-array/commit/9ecd90e2a3e984633f535daa4da3cbfb96964fdd))

### [0.9.5](https://www.github.com/humanwhocodes/config-array/compare/v0.9.4...v0.9.5) (2022-02-23)


### Bug Fixes

* Ensure dot directories are matched correctly ([6e8d180](https://www.github.com/humanwhocodes/config-array/commit/6e8d180f43cedf3c2072d8a1229470e9fafabf5b))
* preprocessConfig should have correct 'this' value ([9641540](https://www.github.com/humanwhocodes/config-array/commit/96415402cf0012ccf8e4af6c7b934dfc1a058986))

### [0.9.4](https://www.github.com/humanwhocodes/config-array/compare/v0.9.3...v0.9.4) (2022-01-27)


### Bug Fixes

* Negated patterns to work when files match ([398c811](https://www.github.com/humanwhocodes/config-array/commit/398c8119d359493dc7b82b40df4d92ea6528375f))

### [0.9.3](https://www.github.com/humanwhocodes/config-array/compare/v0.9.2...v0.9.3) (2022-01-26)


### Bug Fixes

* Make negated ignore patterns work like gitignore ([4ee8e99](https://www.github.com/humanwhocodes/config-array/commit/4ee8e998436e2c4538b06476e0bead8a44fe5a1b))

### [0.9.2](https://www.github.com/humanwhocodes/config-array/compare/v0.9.1...v0.9.2) (2021-11-02)


### Bug Fixes

* Object merging error by upgrading object-schema ([377d06d](https://www.github.com/humanwhocodes/config-array/commit/377d06d2a44d781b0bec70b3389c48b3d5a63f94))

### [0.9.1](https://www.github.com/humanwhocodes/config-array/compare/v0.9.0...v0.9.1) (2021-10-05)


### Bug Fixes

* Properly build package for release ([168155f](https://www.github.com/humanwhocodes/config-array/commit/168155f3fed91ab35566c452efd28debf8ec2b85))

## [0.9.0](https://www.github.com/humanwhocodes/config-array/compare/v0.8.0...v0.9.0) (2021-10-04)


### Features

* getConfig() now returns undefined when no configs match. ([a563b82](https://www.github.com/humanwhocodes/config-array/commit/a563b8255d4eb2bb7745314e3f00ef53792b343f))

## [0.8.0](https://www.github.com/humanwhocodes/config-array/compare/v0.7.0...v0.8.0) (2021-10-01)


### Features

* Add isIgnored() method ([343e5a0](https://www.github.com/humanwhocodes/config-array/commit/343e5a0a9e32028bfc6c0bf1ec0c6badf74f47f9))


### Bug Fixes

* Ensure global ignores are honored ([343e5a0](https://www.github.com/humanwhocodes/config-array/commit/343e5a0a9e32028bfc6c0bf1ec0c6badf74f47f9))

## [0.7.0](https://www.github.com/humanwhocodes/config-array/compare/v0.6.0...v0.7.0) (2021-09-24)


### Features

* Only object configs by default ([5645f24](https://www.github.com/humanwhocodes/config-array/commit/5645f241b2412a3263a02ef9e3a9bd19cc86035d))

## [0.6.0](https://www.github.com/humanwhocodes/config-array/compare/v0.5.0...v0.6.0) (2021-04-20)


### Features

* Add the normalizeSync() method ([3e347f9](https://www.github.com/humanwhocodes/config-array/commit/3e347f9d77c5ca2b15995e75ff7bc4fb96b7d66e))
* Allow async config functions ([a9def0f](https://www.github.com/humanwhocodes/config-array/commit/a9def0faf579c223349dfe08d2486756840538c3))
