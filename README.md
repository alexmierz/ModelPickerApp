# Model Picker App
> An Augmented Reality application to pick and place items in your own space!


Constructed entirely within XCode using the advanced SwiftUI framework, this app seamlessly integrates various essential libraries, including ARKit, RealityKit, UIKit, Combine, and more. The culmination of cutting-edge technologies ensures a robust and immersive user experience.

Empowering users with a unique and engaging interaction, the app allows the seamless selection and placement of diverse 3D models within their physical environment which were found at https://developer.apple.com/augmented-reality/quick-look/. Leveraging the capabilities of augmented reality, this feature opens up endless possibilities for creativity and practical applications. Experience the fusion of design and functionality as you effortlessly integrate digital elements into the real world through our meticulously crafted AR application.

![](img.png)

## Installation

Add this project on your `Package.swift`

```swift
import PackageDescription

let package = Package(
    dependencies: [
        .Package(url: "https://github.com/user/project.git", majorVersion: 0, minor: 0)
    ]
)
```

## Usage example


```swift
import Project
let proj = Class(param: String?)
proj.run()
```


## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
```

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

[swift-image]:https://img.shields.io/badge/swift-3.0-orange.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[codebeat-image]: https://codebeat.co/badges/c19b47ea-2f9d-45df-8458-b2d952fe9dad
[codebeat-url]: https://codebeat.co/projects/github-com-vsouza-awesomeios-com
