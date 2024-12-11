# Apostrophy Flutter Lints

[Flutter](https://flutter.dev) lint rules used by [Apostrophy](https://apostrophy.com/). Built on top of the [officially recommended](https://pub.dev/packages/flutter_lints) linter rules.

[![pub version][pub-version-img]][pub-version-url]

## Usage

### Install

```bash
dart pub add dev:apostrophy_lints
# Or
flutter pub add dev:apostrophy_lints
```

Or add it to the `pubspec.yaml` yourself:

```yaml
dev_dependencies:
  apostrophy_lints: ^1.0.0
```

### Configure analysis options

Modify your [`analysis_options.yaml`](https://dart.dev/tools/analysis#the-analysis-options-file):

```yaml
include: package:apostrophy_lints/analysis_options.yaml
```

## Maintenance

Publishing a new version to pub.dev is automated. To initiate the process, create a new tag with title set to the required version.

<!-- References -->
[pub-version-img]: https://img.shields.io/badge/pub-v1.0.0-0175c2?logo=flutter
[pub-version-url]: https://pub.dev/packages/apostrophy_lints
