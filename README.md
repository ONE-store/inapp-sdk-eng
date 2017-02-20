
> Upload to the GIthub with the one store developer center guide included.

>> 1. ONE store In-app billing SDK and guide are put together and updated at the same time on the Github. 
>> 1. You can check it through [ONE store developer center.](http://dev.onestore.co.kr/devpoc/reference/view/Tool)  


# What is ONE store In-App Purchase? 

ONE store In-App Purchase (hereafter referred to as “IAP”) is an authentification and billing system that allows ONE store users to separately purchase in-app products within an app. If IAP module is applied to developer’s app, ONE store service app identifies the corresponding app and performs the payment process at the time when access to in-app products and payment is requested. ONE store app also allows you to manage the in-app products and check the payment details. 

ONE IAP service structure is as follows:

![enter image description here](https://github.com/ONE-store/inapp-sdk/wiki/images/onestore_inapp_structure.png "ONE store In-app Structure.png")

The IAP module is provided as Java development library, which is called IAP SDK (In-App Purchase Software Development Kit). If the SDK is applied to the developer’s app and functions related to IAP are called, requests are passed to the IAP server. The IAP server generates response data in the JSON format and sends it to the developer’s app. 


# Recommended Development Environment

The following development environment is required to apply the IAP SDK to application for Android.


* Android version 2.3 and above(API version 9 and above)
* [Java SDK version 1.6](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Android studio version 2.0 and above](https://developer.android.com/studio/index.html)

>* The following development environment is recommended for Eclipse.
	* [Eclipse IDE for Java Developers](http://www.eclipse.org/downloads)
	* [ADT Plug-in for Eclipse version 15 and above](http://developer.android.com/sdk/eclipse-adt.html)
