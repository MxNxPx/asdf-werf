# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test werf https://github.com/MxNxPx/asdf-werf.git "werf --help"
```

Tests are automatically run in GitHub Actions on push and PR.
