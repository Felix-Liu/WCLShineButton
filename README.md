# WCLShineButton
[![Version](https://img.shields.io/cocoapods/v/WCLShineButton.svg?style=flat)](http://cocoapods.org/pods/WCLShineButton)
[![License](https://img.shields.io/cocoapods/l/WCLShineButton.svg?style=flat)](http://cocoapods.org/pods/WCLShineButton)
[![Platform](https://img.shields.io/cocoapods/p/WCLShineButton.svg?style=flat)](http://cocoapods.org/pods/WCLShineButton)
[![Support](https://img.shields.io/badge/support-iOS%206%2B%20-blue.svg?style=flat)](https://www.apple.com/nl/ios/)&nbsp;
![Language](https://img.shields.io/badge/Language-%20swift%20%20-blue.svg)


This is a UI lib for iOS. Effects like shining.

![](DemoGif.gif)

#### ![cn](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png) **Chinese (Simplified)**: 
####[中文说明](README.zh.md)
######[博客介绍](http://blog.csdn.net/wang631106979/article/details/55230455)

## **CocoaPods**

CocoaPods is the recommended way to add `WCLShineButton` to your project.

Add a pod entry for `WCLShineButton` to your Podfile.

```
pod 'WCLShineButton'
```

Second, install `WCLShineButton` into your project:

```
pod install
```

Include WCLShineButton wherever you need it with `import WCLShineButton`.

## Usage

```swift
var param1 = WCLShineParams()
param1.bigShineColor = UIColor(rgb: (153,152,38))
param1.smallShineColor = UIColor(rgb: (102,102,102))
let bt1 = WCLShineButton(frame: .init(x: 100, y: 100, width: 60, height: 60), params: param1)
bt1.fillColor = UIColor(rgb: (153,152,38))
bt1.color = UIColor(rgb: (170,170,170))
bt1.addTarget(self, action: #selector(action), for: .touchUpInside)
view.addSubview(bt1)
```

## **Complex Usage**

| **Property**          | **Description**                          |
| --------------------- | ---------------------------------------- |
| color                 | Default button color                     |
| fillColor             | Fill button color                        |
| allowRandomColor      | Allow shine color random                 |
| animDuration          | shine anim duration                      |
| bigShineColor         | big shine color                          |
| enableFlashing        | Enable effect like flash                 |
| shineCount            | shine count around button                |
| shineTurnAngle        | turn angle of shine                      |
| shineDistanceMultiple | multiple of distance to button           |
| smallShineOffsetAngle | angle offset of small shine to big shine |
| smallShineColor       | small shine color                        |
| shineSize             | size of shine by pixel                   |
| colorRandom           | shine color random                       |
| image                 | button image (png)                       |

## **Contacts**

**[blog]( http:blog.imwcl.com)**

**[CSDN](http://blog.csdn.net/wang631106979)**

## Code Reference

[ShineButton](https://github.com/ChadCSong/ShineButton)

## **License**

WCLShineButton is released under the [MIT license](https://github.com/631106979/WCLShineButton/blob/master/LICENSE). See LICENSE for details.

