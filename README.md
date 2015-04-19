# iOS Developer Stack
A list of some of the best and most common iOS developers tools, tricks, script, commands, project settings etc...

Feel free to contribute: [issues](https://github.com/shams-ahmed/ios-developers-stack/issues), [pull requests](https://github.com/shams-ahmed/ios-developers-stack/pulls), or [Twitter](https://twitter.com/shams5035). Get in contact with the developer on Twitter: @shams5035

### Package Manager
* [**Homebrew**](http://brew.sh/) installs the stuff you need that Apple didn’t.   
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)```  
once installed finalise setup:  
```brew update && brew doctor```
* [**Homebrew Cask**](http://caskroom.io/):star2: provides a friendly homebrew-style CLI workflow for the administration of Mac applications distributed as binaries.  
```brew update && brew install caskroom/cask/brew-cask```
* [**CocoaPods**](https://github.com/CocoaPods/CocoaPods):star2: manages dependencies for your Xcode projects. (note: may take a few minutes)  
```sudo gem install cocoapods && pod setup``` 
* [**Carthage**](https://github.com/Carthage/Carthage)  builds your dependencies and provides you with binary frameworks, but allows you to retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.  
```brew install carthage```  
* [**Alcatraz**](http://alcatraz.io/) is an open-source package manager for Xcode 5+. It lets you discover and install plugins, templates and color schemes without the need for manually cloning or copying files. once installed restart XCode and select Package Manager from the Window menu.  
```curl -fsSL https://raw.githubusercontent.com/supermarin/Alcatraz/master/Scripts/install.sh | sh```  
	* [**VVDocumenter**](https://github.com/onevcat/VVDocumenter-Xcode):star2: Xcode plug-in which helps you write Javadoc style documents easier.  
	* [**XToDo**](https://github.com/trawor/XToDo)  Xcode plugin to collect and list the `TODO`,`FIXME`,`???`,`!!!!`
	* [**XcodeColors**](https://github.com/robbiehanson/XcodeColors):star: allows you to use colors in the Xcode debugging console. It's designed to aid in the debugging process.  
	* [**KSImageNamed-Xcode**](https://github.com/ksuther/KSImageNamed-Xcode)  plug-in that provides autocomplete for imageNamed: calls 
	* [**Backlight-for-XCode**](https://github.com/limejelly/Backlight-for-XCode)  Highlights the current editing line in Xcode 
	* [**GitDiff**](https://github.com/johnno1962/GitDiff) displays deltas against a git repo in the Xcode source editor once you've saved the file 
	* [**Xcode way**](https://github.com/onmyway133/XcodeWay):star: Xcode plugin that makes navigating to many places easier  
	* [**ZMDocItemInspector**](https://github.com/zolomatok/ZMDocItemInspector) Xcode plugin converts the Quick Help inspector into an always visible Document Items inspector.
 

### Debug Tool  
* [**Tuna**](https://github.com/dealforest/Tuna) Xcode plugin that provides easy set breakpoint  
* [**Chisel**](https://github.com/facebook/chisel)  Chisel is a collection of LLDB commands to assist debugging iOS apps.  
* [**PonyDebugger**](https://github.com/square/PonyDebugger):star: Remote network and data debugging for your native iOS app using Chrome Developer Tools  
* [**FLEX**](https://github.com/Flipboard/FLEX) An in-app debugging and exploration tool  
* [**APNS-Pusher**](https://github.com/blommegard/APNS-Pusher) A simple debug application for Apple Push Notification Service (APNS)  
* [**WBWebViewConsole**](https://github.com/Naituw/WBWebViewConsole) In-App debug console for your UIWebView & WKWebView  
* [**LLDB-QuickLook**](https://github.com/ryanolsonk/LLDB-QuickLook) Debugger commands to open images, views, and more using Quick Look  
* [**Reveal**](http://revealapp.com/) brings powerful runtime view debugging to iOS developers.  
* [**iOS-Headers**](https://github.com/MP0w/iOS-Headers) iOS 5.0/5.1/6.0/6.1/7.0/7.1/8.0/8.1 Headers of All Frameworks  
* [**class-dump**](https://github.com/nygard/class-dump) Generate Objective-C headers from Mach-O files


### Application and Script  
* [**App code**](https://www.jetbrains.com/objc/) alternative to xcode IDE  
* [**oh-my-zsh**](https://github.com/robbyrussell/oh-my-zsh):star: A community-driven framework for managing your zsh configuration.  
```curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh```  
* [**Sublime**](http://www.sublimetext.com/) Sublime Text is a sophisticated text editor for code, markup and prose.   
```brew cask install sublime-text```  
* [**Unused**](http://jeffhodnett.github.io/Unused/) check Xcode projects for unused resources  
* [**Synx**](https://github.com/venmo/synx) command-line tool that reorganizes your Xcode project folder to match your Xcode groups 
* [**Dash**](https://kapeli.com/dash):star: a API Documentation Browser and Code Snippet Manager.  
* [**Prepo**](http://wearemothership.com/work/prepo/) Prepare, share and preview App artwork and icons  
* [**Flashlight**](https://github.com/nate-parrott/Flashlight) The missing Spotlight plugin system  
```brew cask install flashlight```  


### Quicklook Plugin
* [**qlmarkdown**](https://github.com/toland/qlmarkdown) QuickLook generator for Markdown files
* [**ProvisionQL**](https://github.com/ealeksandrov/ProvisionQL) Quick Look plugin for .ipa and .mobileprovision   
```brew cask install provisionql```  


### Build
* [**XCTool**](https://github.com/facebook/xctool) replacement for Apple's xcodebuild that makes it easier to build & test iOS/OSX apps  
```brew install xctool```
* [**Fastlane**](https://github.com/KrauseFx/fastlane):star2: Connect all iOS deployment tools into one streamlined workflow  
```sudo gem install fastlane```
* [**Shenzhen**](https://github.com/nomad/shenzhen):star: CLI for Building & Distributing iOS Apps (.ipa Files)  
```gem install shenzhen```


### Git (source control)
* [**Objective-c**](https://github.com/github/gitignore/blob/master/Objective-C.gitignore):star: .gitignore list  
* [**Swift**](https://github.com/github/gitignore/blob/master/Swift.gitignore):star: .gitignore list  
* [**Xcode**](https://github.com/github/gitignore/blob/master/Global/Xcode.gitignore) .gitignore list  
* [**OSX**](https://github.com/github/gitignore/blob/master/Global/OSX.gitignore) .gitignore list  


### Design 
* [**iOS app icon**](http://appicontemplate.com/ios8):star: iOS app icon
* [**OSX app icon**](http://appicontemplate.com/osx) OSX app icon
* [**Watch app icon**](http://appicontemplate.com/watch) watch app icon
* [**iPhone screenshot**](http://appicontemplate.com/iphonescreenshot) screenshot marker for iPhone
* [**iPad screenshot**](http://appicontemplate.com/ipadscreenshot) screenshot marker for iPad
* [**iPhone GUI**](http://www.teehanlax.com/tools/iphone/):star: photoshop template of all iOS8 controls
* [**iPad GUI**](http://www.teehanlax.com/tools/ipad/) photoshop template of all iOS8 controls


### Continuous Integration (CI)
* [**Travis-ci**](https://travis-ci.com/):star2: Focus on writing code. Let Travis CI take care of running your tests and deploying your apps.  
* [**Jenkins app**](https://github.com/stisti/jenkins-app) open source ci  
	* [**CocoaPods Plugin**](https://wiki.jenkins-ci.org/display/JENKINS/CocoaPods+Plugin) This plugin provides a build step for projects which use CocoaPods.
	* [**Xcode+Plugin**](https://wiki.jenkins-ci.org/display/JENKINS/Xcode+Plugin) adds the ability to call Xcode command line tools to automate build and packaging iOS applications (iPhone, iPad, ...).  
* [**Coveralls**](https://coveralls.io/) deliver code confidently by showing which parts of your code aren't covered by your test suite.  


### Command Line
* Quick Look text selection
```defaults write com.apple.finder QLEnableTextSelection -bool TRUE; killall Finder```


### XCode Project
* Use plain “DWARF” instead of “DWARF with dSYM File” as your “Debug Information Format”.
* Don’t compile your project code or use static libraries compiled with -O4 since it tells Clang to enable Link Time Optimizations (LTO) making the linking stage much slower. Use -O3 at most.
* Use forward declaration instead of having headers include were possible
* set Build Settings / Architectures / Build Active Architecture Only to YES.
* create ramdisk for iOS sim, derived data etc. only if you have 16gb ram. see [xcode_ramdisk.sh](https://gist.github.com/skeeet/2367298)


### More Ideas
add star system of highly recommended


### License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)  
To the extent possible under law, [Shams Ahmed](https://twitter.com/shams5035) has waived all copyright and related or neighboring rights to this work.  

