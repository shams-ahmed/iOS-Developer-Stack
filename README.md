# iOS Developers Stack
A great list of the best and most common iOS developers tools to get you started with development on your Mac computer!  

Feel free to contribute: [issues](https://github.com/shams-ahmed/ios-developers-stack/issues), [pull requests](https://github.com/shams-ahmed/ios-developers-stack/pulls), or [Twitter](https://twitter.com/shams5035). Get in contact with the developer on Twitter: @shams5035

### Package manager
* [**Homebrew**](http://brew.sh/) installs the stuff you need that Apple didn’t.   
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)```  
once installed finalise setup:  
```brew update && brew doctor```

* [**Homebrew Cask**](http://caskroom.io/) provides a friendly homebrew-style CLI workflow for the administration of Mac applications distributed as binaries.  
```brew update && brew install caskroom/cask/brew-cask```

* [**CocoaPods**](https://github.com/CocoaPods/CocoaPods) manages dependencies for your Xcode projects. (note: may take a few minutes)  
```sudo gem install cocoapods && pod setup``` 
* [**Carthage**](https://github.com/Carthage/Carthage)  builds your dependencies and provides you with binary frameworks, but allows you to retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.  
```brew install carthage```  

* [**Alcatraz**](http://alcatraz.io/) is an open-source package manager for Xcode 5+. It lets you discover and install plugins, templates and color schemes without the need for manually cloning or copying files.  
```curl -fsSL https://raw.githubusercontent.com/supermarin/Alcatraz/master/Scripts/install.sh | sh```  
once installed restart XCode and select Package Manager from the Window menu.  
	* [**VVDocumenter**](https://github.com/onevcat/VVDocumenter-Xcode)  Xcode plug-in which helps you write Javadoc style documents easier.  
	* [**XToDo**](https://github.com/trawor/XToDo)  Xcode plugin to collect and list the `TODO`,`FIXME`,`???`,`!!!!`
	* [**XcodeColors**](https://github.com/robbiehanson/XcodeColors)  allows you to use colors in the Xcode debugging console. It's designed to aid in the debugging process.  
	* [**KSImageNamed-Xcode**](https://github.com/ksuther/KSImageNamed-Xcode)  plug-in that provides autocomplete for imageNamed: calls 
	* [**Backlight-for-XCode**](https://github.com/limejelly/Backlight-for-XCode)  Highlights the current editing line in Xcode 
	* [**GitDiff**](https://github.com/johnno1962/GitDiff)  displays deltas against a git repo in the Xcode source editor once you've saved the file  
	* [**Tuna**](https://github.com/dealforest/Tuna)  Xcode plugin that provides easy set breakpoint
	* [**Chisel**](https://github.com/facebook/chisel)  Chisel is a collection of LLDB commands to assist debugging iOS apps.
 



### More Ideas
add star system of highly recommended  
### License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)  
To the extent possible under law, [Shams Ahmed](https://twitter.com/shams5035) has waived all copyright and related or neighboring rights to this work.  


