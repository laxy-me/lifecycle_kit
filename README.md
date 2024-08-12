# lifecycle_kit

> 经历了好几个 Flutter 版本更新后深有体会，这项目还是放到工程项目里的 packages 文件夹下本地应用会比较好 ...
> 方便随 Flutter 版本更新而更新 ...

[![Pub Package](https://img.shields.io/pub/v/lifecycle_kit.svg)](https://pub.dev/packages/lifecycle_kit)
[![License](https://img.shields.io/github/license/RxReader/lifecycle_kit)](https://github.com/RxReader/lifecycle_kit/blob/master/LICENSE)

A powerful package for Flutter.

## flutter

* snapshot

```
dependencies:
  lifecycle_kit:
    git:
      url: https://github.com/RxReader/lifecycle_kit.git
```

* release

```
dependencies:
  lifecycle_kit: ^${latestTag}
```

* demo

```shell
cd example/
flutter pub run build_runner clean
flutter pub run build_runner build --delete-conflicting-outputs
```
