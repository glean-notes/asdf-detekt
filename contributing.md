# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test detekt https://github.com/glean-notes/asdf-detekt.git "detekt --version"
```

Tests are automatically run in GitHub Actions on push and PR.
