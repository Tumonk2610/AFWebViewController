AFWebViewController
===================
![Pod version](http://img.shields.io/cocoapods/v/AFWebViewController.svg?style=flat)
![Pod platform](http://img.shields.io/cocoapods/p/AFWebViewController.svg?style=flat)
[![Build Status](http://img.shields.io/travis/Fogh/AFWebViewController.svg?style=flat)](https://travis-ci.org/Fogh/AFWebViewController)

In-app browser

## Description

In-app browser for quick implementation in your app. Pretty much inspired by [SVWebViewController](https://github.com/TransitApp/SVWebViewController). 
Uses [WKWebView](https://developer.apple.com/library/IOs/documentation/WebKit/Reference/WKWebView_Ref/index.html) for a much faster browsing experience. 

**Requires iOS 8+**

## Usage example

Push AFWebViewController:
```objectivec
AFWebViewController *webViewController = [AFWebViewController webViewControllerWithAddress:@"https://google.com"];
```

Modal AFWebViewController:
```objectivec
AFModalWebViewController *webViewController = [AFModalWebViewController webViewControllerWithAddress:@"https://google.com"];
```

---
<a href="http://Fogh.tip.me">
  <img
    alt="Tip Me With ChangeTip"
    src="https://cdn.changetip.com/img/logos/tipme_square.png?1"/>
</a>
