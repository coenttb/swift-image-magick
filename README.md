# SwiftImageMagick

**SwiftImageMagick** is a Swift library that wraps around the powerful ImageMagick C library, enabling efficient image manipulation and processing with a Swift-native API.

## Features

- Swift-friendly interface for ImageMagick.
- Perform operations like:
  - Text Metrics: Calculate text properties (width, height, ascender, descender, bounding box, etc.).
  - Image Manipulation: Resize, transform, and process images.

## Installation

### Prerequisites

1. **ImageMagick** must be installed on your system.

   - On macOS (Homebrew):
     ```bash
     brew install imagemagick
     ```

   - On Linux (Debian/Ubuntu):
     ```bash
     sudo apt-get update
     sudo apt-get install libmagickwand-dev
     ```

2. **Swift Package Manager** Add `SwiftImageMagick` to your `Package.swift` dependencies:

```swift

let package = Package(
    name: "YourProject",
    dependencies: [
        .package(url: "https://github.com/coenttb/swift-image-magick.git", branch: "main")
    ],
    targets: [
        .target(name: "YourProject", dependencies: ["SwiftImageMagick"])
    ]
)
```

## Related Packages

This package has no dependencies and is not currently used by other packages in the ecosystem.

## Feedback is much appreciated!

If you’re working on your own Swift project, feel free to learn, fork, and contribute.

Got thoughts? Found something you love? Something you hate? Let me know! Your feedback helps make this project better for everyone. Open an issue or start a discussion—I’m all ears.

> [Subscribe to my newsletter](http://coenttb.com/en/newsletter/subscribe)
>
> [Follow me on X](http://x.com/coenttb)
> 
> [Link on Linkedin](https://www.linkedin.com/in/tenthijeboonkkamp)

## License

This project is licensed by coenttb under the Apache 2.0 License. See [LICENSE](LICENSE) for details.
