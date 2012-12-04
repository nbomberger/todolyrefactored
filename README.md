Todoly Refactored
=================

### Todoly Refactored - Add network caching using CoreData 

#### Overview

We recently needed to build an application that could synchronize data across a website and multiple mobile devices.  This is a pretty common situation for any one working with any technolgies using any part of the web stack.  There is nothing fancy in this post, but demonstrates a simple roll-your-own caching solution utilizing a cloud service backend. Our focus is on the mobile side.  

The goal of this post is to discuss a method to add the ability to cache network queries using the [CloudMine iOS SDK][CloudMineIoslibrary].  Adding this capability will allow us to continue to allow the application to function when we don't have access to the network.  [CloudMine][CloudMine] is a backend-as-service platform that provides easy access to the cloud.  Our application will really just be a refactor of an application built by the engineers at [CloudMine][CloudMine], [Todoly][todolyportal]. According to [CloudMine][CloudMine], [Todoly][CloudMineIoslibrary] is: 

>    *A simple application that demonstrates CloudMine's user authentication and object storage APIs. It displays a simple, per-user todo list, and just happens to sync with this [JavaScript sample application][todolyportal].*


By bridging the storage capability inherant in CloudMine and CoreData, we add flexibility to the application which could allow for alternative storage solutions if warranted, and allow the user to continue use the application even when access to the cloud is not possible.

##### iOS component
Below is a list of the technologies we used to refactor the application in the simulator or device.  You will need to have a CloudMine account, as well as an Apple Developer account in order to run this provided [demo source code][todolyrefactoredsource].  
* [Xcode 4.5][xcode4.5] - IDE for iOS development.
* [CloudCloudMine Javascript Library][CloudMineJavascriptLibrary] - backend-as-a-service Javascript API Library.
* [CloudMine iOS SDK][CloudMineIoslibrary] - iOS backend-as-a-service SDK.
* [MagicRecord][MagicRecord] - Helper classes to facilitate using CoreData on iOS.
* [Reachability.h][Reachability.h] - Apple provided classes to assist in detecting network status on iOS device.


##### Web Component 
[CloudMine][CloudMine] also provides the web client source code which can be downloaded [here][todolyportal].

    
<!-- Embed html or javascript using the below -->
</script>
<center>

<div id="price-widget"></div>
</center>

 <!-- Links to images, hyperlinks should go here -->
 [CloudMine]: http://www.cloudmine.me
 [CloudMineIoslibrary]: https://cloudmine.me/docs/ios
 [CloudMineJavascriptLibrary]: https://cloudmine.me/docs/js
 [todolyportal]: https://cloudmine.me/sample-apps/todo/index.html 
 [todolyrefactoredsource]: http://github.com/nbomberger/todolyrefactored
 [Arcweb]: http://www.arcwebl.co
  <!-- Tool links -->
 [xcode4.5]: http://developer.apple.com/xcode
 [MagicRecord]: https://github.com/magicalpanda/MagicalRecord
 [Reachability.h]: http://developer.apple.com/library/ios/#samplecode/Reachability/Listings/Classes_Reachability_h.html 
 [README.md]: http://github.com/nbomberger/totallyrefactored 