# pre-commit-rust-hook
Simple [pre-commit](https://pre-commit.com) hooks for rust

Current hooks are:
* ```rustfmt``` - run rustfmt on all rust text files and change the file

* ```rustfmt-check``` - run rustfmt in check mode and report failure (no files are changed)

## Example Usage

Add the following to ```.pre-commit-config.yaml```

```yaml
repos:
-   repo: https://github.com/billyrayvalentine/pre-commit-rust-hook
    rev: 0.1.0
    hooks:
    -   id: rustfmt
```
