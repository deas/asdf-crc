# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test crc https://github.com/deas/asdf-crc.git "crc --help"
```

Tests are automatically run in GitHub Actions on push and PR.
