A set of custom lint rules for Flutter apps and packages.

This package is built on top of the set of lints defined by the package [dart_lint_rules](https://github.com/fabriziocacicia/dart_lint_rules).

## Usage

1. Depend on this package as a dev_dependency by adding it as a git 
   dependency ([see how](https://dart.dev/tools/pub/dependencies#git-packages))
2. Create an `analysis_options.yaml` file at the root of the package (alongside the `pubspec.yaml` file) and include: 
   `package:flutter_lint_rules/apps.yaml` or `package:flutter_lint_rules/packages.yaml` from it.
    