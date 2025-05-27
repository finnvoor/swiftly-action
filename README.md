# swiftly-action

A Github Action for installing Swiftly on macOS and Linux. A toolchain specified in a `.swift-version` file at the root of the repository will automatically be installed.

### Usage

```yaml
jobs:
  test:
    steps:
      - uses: actions/checkout@v4
      - uses: finnvoor/swiftly-action@main
```
