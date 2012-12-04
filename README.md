#### Installation

There are two components you will need to install in order to test this application.  There is a web component, [Todoly][todolyportal] and the [iOS application][todolyios].  

###### CloudMine Setup
1. Sign in to [CloudMine Dashboard][CloudMineDashboard].
2. Click on `My Apps`.
3. Enter `TodolyRefactored`.
4. Save `Application ID` somewhere save.  This identifies your application with [CloudMine][CloudMine].

<!-- appid: ec2c161f7a4b485981230a7b0a28f3fe -->
<!-- apikey: e1767a2e93824f219d75969ee64cbff1 -->

###### Get Source Code 
*Note: These instructions assume you are on OS X.*

1.  Download [source][todolyrefactoredsource]. Open up a terminal and issue the following command:
		
		$ git clone https://github.com/nbomberger/TodolyRefactoredored

2. Change to the `web` directory:  
		
		$ cd todolyrefactored/web

3.  Start the up a local web server:	
	
		$ python -m SimpleHTTPServer & 

4.  Open `index.html` in a browser:  

		$ open index.html

5.  Profit!
		

###### Setting up Test Environment



<!-- Links -->

 [todolyios]: https://github.com/cloudmine/cloudmine-ios-sample-todo 
 [CloudMineDashboard]: https://cloudmine.me/dashboard 
 [CloudMine]: http://www.cloudmine.me
 [CloudMineIoslibrary]: https://cloudmine.me/docs/ios
 [CloudMineJavascriptLibrary]: https://cloudmine.me/docs/js
 [todolyportal]: https://cloudmine.me/sample-apps/todo/index.html 
 [todolyrefactoredsource]: https://github.com/nbomberger/todolyrefactored 
 [Arcweb]: http://www.arcwebl.co
  <!-- Tool links -->
 [xcode4.5]: http://developer.apple.com/xcode
 [MagicRecord]: https://github.com/magicalpanda/MagicalRecord
 [Reachability.h]: http://developer.apple.com/library/ios/#samplecode/Reachability/Listings/Classes_Reachability_h.html 
 [README.md]: http://github.com/nbomberger/totallyrefactored 