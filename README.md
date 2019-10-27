# LPZeroMQ


**LPZeroMQ** provides ZeroMQ for **Swift 5.1**.

Reference : [https://github.com/Zewo/CZeroMQ.git](https://github.com/Zewo/CZeroMQ.git)

## Installation


```bash
$ sudo apt-get install libzmq3-dev
```

- Add `LPZeroMQ` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Linzecong/LPZeroMQ.git", majorVersion: 1)
	]
)

```
