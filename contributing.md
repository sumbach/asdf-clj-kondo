# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test clj-kondo https://github.com/sumbach/asdf-clj-kondo.git "clj-kondo --version"
```

Tests are automatically run in GitHub Actions on push and PR.
