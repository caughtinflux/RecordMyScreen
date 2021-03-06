## RecordMyScreen

Record the display even on non-jailbroken iPhones.

Licenced with the MIT Licence with the following 2 clauses added onto it:
You may not use the source code for any commercial product.
You may use the videos created from RecordMyScreen for commercial use.

## Credits

* CoolStar (@coolstarorg) - Started the project, and created the initial code.
* ProtoSphere (@protosphere7) - Helped transition to encoding the video on-the-fly
* John Coates (@punksomething) - Improved the framerate of the video captured, fixed the screen tearing, and made RecordMyScreen usable on <= A4
* Brandon Etheredge (@brandonEtheredg) - Added support for the iPad on the UI
* Nicholas Gomolion - Prevented other apps from stopping our recording (unfortunately using an iOS 6 only API)

## Technical Specs

1. ARMv7 device (A5 recommended)
2. iOS 5 or higher (iOS 6 recommended, may work on iOS 4)
3. Developer Account or Jailbreak to install
4. XCode 4.4.1 or higher

## Device Compatibility

iPhones

1. iPhone 3GS
2. iPhone 4
3. iPhone 4S
4. iPhone 5

Notes:

* iPhone 2G - Not supported: iOS 3 is too ancient, armv6, way too slow, no h.264 encoding support
* iPhone 3G - Not supported: armv6, too slow, does this even support h.264 encoding?

iPod touch

1. iPod touch 3G
2. iPod touch 4
3. iPod touch 5

Notes:

* iPod touch 1G - Not Supported: No microphone, iOS 3 is too ancient, armv6, way too slow, no h.264 encoding support
* iPod touch 2G - Not Supported: armv6, probably doesn't support h.264 encoding
* iPod touch 2G and 3G will need a headset with mic plugged into the headphone jack for backgrounding to work

iPad's

1. iPad 1 (maybe, test please?)
2. iPad 2

Note: iPads with Retina Display are not supported due to Issue [#8](https://github.com/coolstar/RecordMyScreen/issues/8)

## Jailbroken users without access to a Mac+XCode

You may download the latest build of the last stable release (1.0) here: http://d.pr/f/Hnsw
