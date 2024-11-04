# Contributing

Testing Locally:

```shell
mise plugin test <plugin-name> <plugin-url> [--mise-tool-version <version>] [--mise-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
mise plugin test chefvm https://github.com/elijah/mise-chefvm.git "chefvm version"
```

Tests are automatically run in GitHub Actions on push and PR.
