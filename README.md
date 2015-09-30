# Vungle's Cocos2d (http://www.cocos2d-objc.org/) sample

## Getting Started
To get up and running with Vungle, you'll need to [Create an Account With Vungle](https://v.vungle.com/dashboard/signup) and [Add an Application to the Vungle Dashboard](https://support.vungle.com/hc/en-us/articles/204249614-Adding-an-Application-to-the-Vungle-Dashboard)

Once you've created an account you can follow our [Getting Started for iOS Guide](https://support.vungle.com/hc/en-us/articles/204430550-Getting-Started-with-Vungle-iOS-SDK) to complete the integration. Remember to get the Vungle App ID from the Vungle dashboard.

### Version Info
The Vungle iOS SDK only supports iOS 7+ and supports both 32bit and 64bit apps.  

Our newest iOS SDK (3.2.0) was released in support of the newest XCode 6.4. Please ensure you are using XCode 6.4 or higher to ensure smooth integration.

## Release Notes
### 3.2.0.*
* This SDK supports iOS 7+ devices only
* Enabled SSL as default for all internal network requests
* Improved caching performance
* Resolved race-condition crash around fetchConfig request
* Unified adPlayable behavior across flags & events
* Fix for playAd return code inconsistency during streaming ad plays
* Fix for progress bar location on smaller screens
* Fix for AppStore failing to load on some occasions
* Fix for issues resulting in inaccessible postroll


## License
The Vungle iOS-SDK is available under a commercial license. See the LICENSE file for more info.
