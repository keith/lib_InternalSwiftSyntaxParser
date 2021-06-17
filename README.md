# lib_InternalSwiftSyntaxParser

This repo vendors binary downloads of the
`lib_InternalSwiftSyntaxParser` dynamic library. This allows you to work
around [this](https://www.smileykeith.com/2021/03/03/editing-rpaths/)
[issue](https://github.com/apple/swift/pull/36151) by vendoring this
library alongside your tool that depends on
[`SwiftSyntax`](https://github.com/apple/swift-syntax)

Download the library for your Xcode version from the [releases
page](https://github.com/keith/lib_InternalSwiftSyntaxParser/releases)
you can see the mapping of versions to tags in the [`SwiftSyntax`
README](https://github.com/apple/swift-syntax#usage)
