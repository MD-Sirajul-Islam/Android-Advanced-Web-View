# Android-Advanced-Web-View

# WebView

public class WebView
extends AbsoluteLayout implements ViewTreeObserver.OnGlobalFocusChangeListener, ViewGroup.OnHierarchyChangeListener 

java.lang.Object
   ↳ 	android.view.View
  	   ↳ 	android.view.ViewGroup
  	  	   ↳ 	android.widget.AbsoluteLayout
  	  	  	   ↳ 	android.webkit.WebView

A View that displays web pages. 
# Basic usage

In most cases, we recommend using a standard web browser, like Chrome, to deliver content to the user. To learn more about web browsers, read the guide on invoking a browser with an intent.

WebView objects allow you to display web content as part of your activity layout, but lack some of the features of fully-developed browsers. A WebView is useful when you need increased control over the UI and advanced configuration options that will allow you to embed web pages in a specially-designed environment for your app.

To learn more about WebView and alternatives for serving web content, read the documentation on Web-based content. 
