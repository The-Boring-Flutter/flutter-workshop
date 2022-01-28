# IOS ISSUES

## Class AMSupportURLConnectionDelegate is implemented Issues.

Promblem:

```
objc[8902]: Class AMSupportURLConnectionDelegate is implemented in both /usr/lib/libauthinstall.dylib (0x201c0eb90)
and /Library/Apple/System/Library/PrivateFrameworks/MobileDevice.framework/Versions/A/MobileDevice (0x103be02c8).
One of the two will be used. Which one is undefined.
```
Solution: Method 1 :
` sudo xcode-select -r ` run the command and again run the command.

Method 2:

Run a new xcode project.
