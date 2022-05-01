# SwiftTools

Docker image for Swift tools.

## Available tools

- [SwiftLint - 0.47.1](https://github.com/realm/SwiftLint)
- [SwiftFormat - 0.49.7](https://github.com/nicklockwood/SwiftFormat)

## Usage

```sh
docker pull ghcr.io/lgaches/swifttools:latest
```

You can run `swiftlint` or `swiftformat` inside of docker like:

```sh
docker run -it -v `pwd`:`pwd` -w `pwd` ghcr.io/lgaches/swifttools:latest swiftlint
```

```sh
docker run -it -v `pwd`:`pwd` -w `pwd` ghcr.io/lgaches/swifttools:latest swiftformat .
```
