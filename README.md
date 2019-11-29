# BFLoadingView

[![Version](https://img.shields.io/cocoapods/v/BFLoadingView.svg?style=flat)](https://cocoapods.org/pods/BFLoadingView)
[![License](https://img.shields.io/cocoapods/l/BFLoadingView.svg?style=flat)](https://cocoapods.org/pods/BFLoadingView)
[![Platform](https://img.shields.io/cocoapods/p/BFLoadingView.svg?style=flat)](https://cocoapods.org/pods/BFLoadingView)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Usage

BFLoadingView is a nice morphing poligonal activity indicator design as an animating HUD. Try to add it to your `UIViewController` and you should get the following result:

![](animation.gif)

### Use it!

First you have to import the BFLoadingView Library by adding `import BFLoadingView`.

Then call the following when you want to show the animated activity indicator. The fade in duration is 0.25 seconds:
```swift
showLoadingView()
```
When you are done with your task in code you can also hide the indicator again by the following function:

```swift
hideLoadingView()
```

That's it. Have fun!

## Installation

BFLoadingView is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'BFLoadingView'
```

## Author

Matthias Nagel, matthias@bitfactory.io

## License

BFLoadingView is available under the MIT license. See the LICENSE file for more info.
