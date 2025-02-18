# Changelog

### [2.2.1](https://www.github.com/mattpodraza/webview2/compare/v2.2.0...v2.2.1) (2021-05-25)


### Bug Fixes

* add setters for missing options, provide reasonable defaults ([f3d7d2e](https://www.github.com/mattpodraza/webview2/commit/f3d7d2e5e4c68b992449d281a1e67745e702de8b))

## [2.2.0](https://www.github.com/mattpodraza/webview2/compare/v2.1.1...v2.2.0) (2021-05-16)


### Features

* add a Handle function that returns the window handle for better control of the window outside of this package. ([b64a658](https://www.github.com/mattpodraza/webview2/commit/b64a65832852d1f04c370992c076a8c79ee4ba23))
* add Minimize, Restore, and Maximize window functions. ([b64a658](https://www.github.com/mattpodraza/webview2/commit/b64a65832852d1f04c370992c076a8c79ee4ba23))
* add support for the rest of WebView settings ([0720c85](https://www.github.com/mattpodraza/webview2/commit/0720c85c729100c8b441118e89a6555406a24c4a))

### [2.1.1](https://www.github.com/mattpodraza/webview2/compare/v2.1.0...v2.1.1) (2021-05-16)


### Bug Fixes

* **com:** proper ordering of COM object methods ([786d915](https://www.github.com/mattpodraza/webview2/commit/786d915bd2b1b51fc547c359ff9dd5baef10abd0))
* **user32:** rely on the return value of GetMessage instead of the error return value ([adafe38](https://www.github.com/mattpodraza/webview2/commit/adafe38d637c276659af1111c2f917ac534ab1c5))

## [2.1.0](https://www.github.com/mattpodraza/webview2/compare/v2.0.1...v2.1.0) (2021-05-15)


### Features

* bring back support for Eval (now called ExecuteScript) and Init (now called AddScriptToExecuteOnDocumentCreated) ([8a9301d](https://www.github.com/mattpodraza/webview2/commit/8a9301d62c3cf44bd1020ef20de67a5a7e88beb4))
* expose the browser and window structs, make a bit more functions public ([f02b298](https://www.github.com/mattpodraza/webview2/commit/f02b298c57c65bb933c1ebf5a07a72fe3944e319))

### [2.0.1](https://www.github.com/mattpodraza/webview2/compare/v2.0.0...v2.0.1) (2021-05-15)


### Chores

* on second thought, let's keep the generated files in the repo ([7f981d0](https://www.github.com/mattpodraza/webview2/commit/7f981d0579a535b2db8a3067cab981aa83a3c20a))

## [2.0.0](https://www.github.com/mattpodraza/webview2/compare/v1.0.1...v2.0.0) (2021-05-15)


### ⚠ BREAKING CHANGES

* bump module to v2
* add support for changing WebView settings

### Features

* add a com package for handling calls to the WebView COM objects ([1576395](https://www.github.com/mattpodraza/webview2/commit/15763954d9eb980eaa068ac2723039d71a877181))
* add a helper package for handling mapping HRESULT values ([53a4d32](https://www.github.com/mattpodraza/webview2/commit/53a4d32b9fcb8d68157ca487df1734bbea9f5493))
* add support for changing WebView settings ([f770ec0](https://www.github.com/mattpodraza/webview2/commit/f770ec073c604c4b00375a5a46dbf4a799a22ac1))


### Chores

* bump module to v2 ([771d662](https://www.github.com/mattpodraza/webview2/commit/771d6620796f94efb4bd52aa2c531133d295f5f0))
* bump the WebViewLoader2.dll ([8dfb93f](https://www.github.com/mattpodraza/webview2/commit/8dfb93f5f437dd06b52811f2afdc39bc0b4e6d4c))


### Documentation

* update examples ([128fafe](https://www.github.com/mattpodraza/webview2/commit/128fafebd08b3b0d6de0d7af518738d143fb8895))
* update the readme and license to point to this being a derived work based on two upstream repos ([f00697e](https://www.github.com/mattpodraza/webview2/commit/f00697eb6c9f1c44dcd3271666c74e19002383d1))

### [1.0.1](https://www.github.com/mattpodraza/webview2/compare/v1.0.0...v1.0.1) (2021-05-03)


### CI

* fix the release name ([de625fe](https://www.github.com/mattpodraza/webview2/commit/de625fe9a2e653f8977adca691d24846a31f4962))


### Chores

* start showing CI commits in the changelog ([b41dd23](https://www.github.com/mattpodraza/webview2/commit/b41dd2375099b702c87f341c99915b2ff66daf5d))

## 1.0.0 (2021-05-03)


### ⚠ BREAKING CHANGES

* introduce better error handling, use the user32 helper
* embed DLLs using the `go:embed` directive
* change the import path, bump min. Go to 1.16

### Features

* add the `user32` package which wraps many of the syscall calls ([17e76a9](https://www.github.com/mattpodraza/webview2/commit/17e76a9678310a602f70b85ca28e65ab3ed9c883))


### Documentation

* add a minimal example ([4e9cb5d](https://www.github.com/mattpodraza/webview2/commit/4e9cb5d45ca7cbaf229ecc06a5a064da2979520a))
* update LICENSE ([5634e48](https://www.github.com/mattpodraza/webview2/commit/5634e48a4f8c3c55b907db07a7bf9b26c7999554))
* update README.md ([f8b3120](https://www.github.com/mattpodraza/webview2/commit/f8b3120cce0d497540289bfa754210c86f5c05a6))


### Chores

* ignore .vscode and built binaries ([104afbe](https://www.github.com/mattpodraza/webview2/commit/104afbe1b72716d4f7018b8edaea1a03bfcd3f0a))


### Refactoring

* change the import path, bump min. Go to 1.16 ([cbf6f57](https://www.github.com/mattpodraza/webview2/commit/cbf6f57c5e76d19147804fe6dd288e1cb2b79275))
* embed DLLs using the `go:embed` directive ([b287646](https://www.github.com/mattpodraza/webview2/commit/b287646acdcd485ef1c3d4068a48d4603e213868))
* introduce better error handling, use the user32 helper ([09698be](https://www.github.com/mattpodraza/webview2/commit/09698be696bc23cbb4389ffb58c787a502e41560))
