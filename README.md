# GaugeMeterView

GaugeMeterView can be used for create meter indicators which give ability for customizations.

## Installation
Via [CocoaPods](http://cocoapods.org):
```ruby
pod 'GaugeMeterView'

```

## Usage

You can use such code:

```swift

let gaugeMeterView = GaugeMeterView()

gaugeMeterView.gaugeAngle = 30.0
gaugeMeterView.gaugeValuesScale = 2.0

gaugeMeterView.ranges = [(value: 100.0, color: blue, title: "Low"), (value: 200, color: green, title: "Medium"), (value: 300.0, color: red, title: "High")]

```

## Compatibility/Restrictions
* iOS8+ only
