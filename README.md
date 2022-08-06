# Flutter Analyze `pre-commit` with fvm

[`pre-commit`](https://pre-commit.com) hook for running Flutter anlyzer

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/noriHanda/fvm-flutter-analyze-pre-commit
  rev: "master"
  hooks:
    - id: fvm-flutter-analyze
```

## Acknowledgements

[Charles Crete](https://github.com/Cretezy/) for creating `flutter-format-pre-commit`
[Nori Handa](https://github.com/noriHanda) for modifying `flutter-format-pre-commit` to use fvm
