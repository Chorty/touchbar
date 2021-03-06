# touchbar
Apple MacBook Pro TouchBar (NSTouchBar) Cheat Sheet

## How to enable the TouchBar simulator
To enable the `TouchBar` simulator you need `Xcode Version 8.1 (8B62) ` and `macOS 10.12.1` build `12B2657`. You can update Xcode via AppStore. To check your macOS build type in your Terminal

```
$ sw_vers
ProductName:	Mac OS X
ProductVersion:	10.12.1
BuildVersion:	16B265
```

If you are running the previous build of `10.12.1` (16B2555), you have to manually update from Apple Support: https://support.apple.com/kb/dl1897?locale=en_US

Assumed you did the previous steps, open Xcode and the Window menu should look like

![schermata 2016-10-31 alle 19 56 51](https://cloud.githubusercontent.com/assets/163333/19867500/5888c9ce-9fa4-11e6-9ad9-b490e8863341.jpg)

so you should see the `Show Touch Bar` option just after the Organizer option.

## The TouchBar Cheat Sheet
![touchbar_layout_cheatsheet](https://cloud.githubusercontent.com/assets/163333/19802765/82767df4-9d05-11e6-8a21-71359fac1afb.png)

## Launch the Touch Bar simulator programmatically
The [TouchBarLauncher](https://github.com/zats/TouchBarLauncher) Xcode program in Swift, let you run the Touch Bar simulator programmatically and it's very handy. Made by [Sash Zats](https://github.com/zats) it uses the simulator host window controller `IDETouchBarSimulatorHostWindowController` to leverage the TouchBar.

## Touch Bar integrations
[React Native TouchBar](https://github.com/ptmt/react-native-touchbar) is a [React Native](https://github.com/facebook/react-native) component that adds support for the macOS `TouchBar` in React Native.

## References
- [About the TouchBar]( https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/AbouttheTouchBar.html)
- [Visual Design](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/VisualDesign.html#//apple_ref/doc/uid/20000957-CH106-SW1) 
- [Interaction and Gestures](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/Interaction.html#//apple_ref/doc/uid/20000957-CH105-SW1)
- [TouchBar Icons](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/Icons.html#//apple_ref/doc/uid/20000957-CH107-SW1)
- [TouchBar Controls](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/ControlsandViews.html#//apple_ref/doc/uid/20000957-CH108-SW1)
