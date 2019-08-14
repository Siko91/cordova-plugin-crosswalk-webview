# cordova-plugin-crosswalk-webview

Makes your Cordova application use the [Crosswalk WebView](https://crosswalk-project.org/)
instead of the System WebView. Requires cordova-android 4.0 or greater.

> For more detail, go [here](https://github.com/crosswalk-project/cordova-plugin-crosswalk-webview)

# installation

1. install directly with repo url (unstable)

`cordova plugin add https://github.com/YES-Lee/cordova-plugin-crosswalk-webview.git`

2. download repo and install with repo path (recommanded)

`git clone https://github.com/YES-Lee/cordova-plugin-crosswalk-webview.git`
`cordova plugin add /your path/cordova-plugin-crosswalk-webview`

# NOTE

* remove `requireCordovaModule` to compatible with `Cordova 9.x`
* change gradle `leftShift` to `doLast`
