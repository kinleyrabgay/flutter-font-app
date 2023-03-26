# DDC Font App

This is the project code for DDC Font app. Do check out locally and update or refector the code with suitable message.

## Note on iOS part

The installing and uninstalling of the fonts is done with the CoreText API of Apple using the CTFontManager functions.
To communicate to the Native Platform from the FLutter side, we used MethodChanells and injected the native code.

Note: To test it on android studio on a mac, you need additional cocoapods installation to work with it.
There was library dependency issues in our side, so the solution was to edit the code on Android Studio but run it from xCode which worked for testing purposes.
