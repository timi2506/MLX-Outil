# MLX-Outil

MLX Outil is a multiplatform Swift project to show tool usage with Llama 3.2 3B model using MLX Swift across iOS, macOS, and visionOS platforms.

![Platforms](https://img.shields.io/badge/Platforms-iOS%2016.0+%20|%20macOS%2013.0+%20|%20visionOS%201.0+-lightgrey)
![Swift](https://img.shields.io/badge/Swift-6.0-orange)
![MLX](https://img.shields.io/badge/MLX-latest-blue)

## Features

- Tool use demonstrations using Llama 3.2 3B model
- Cross-platform support (iOS, macOS, visionOS)
- On-device inference using MLX Swift
- Example tools implementation:
  - Weather information
  - Web search simulation [pending]

## Requirements

- Xcode 15.0+
- iOS 16.0+
- macOS 13.0+
- visionOS 1.0+
- Swift 6.0
- MLX Swift (latest version)

## Installation

- Clone the repository:
```bash
git clone https://github.com/rudrankriyam/mlx-outil.git
cd mlx-outil
```

- Open `MLXOutil.xcodeproj` in Xcode

```swift
// Initialize view with SwiftUI
MLXOutilView()
    .environmentObject(MLXModel())
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- MLX team for the Swift implementation
- Meta AI for the Llama 3.2 models

## Contact
For questions and support, please open an issue in the repository.
