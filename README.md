# Carthage Specifications

[AppLovinSDK](https://developer.applovin.com) does not support Carthage at this time. This repository offers a workaround to include raw frameworks in your project. All you have to do is to refer to that JSON url in your Cartfile.

## Installation

There are two ways to install AppLovinSDK

### Carthage

Add following line to your `Cartfile`:

```
binary "https://raw.githubusercontent.com/gumob/AppLovinSDK/master/Carthage/iOS/AppLovinSDK.json"
```


### CocoaPods

Add the following line to your `Podfile`:

```
pod 'AppLovinSDK'
```

Run the following on the command line.

```
pod install --repo-update
```
