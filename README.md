# code-better

This is a self help repo for me to keep track of my journy as I challenge myself to code better.

Mostly this is for iOS development, but who knows what else will be in here.



I've been watching some videos from Sean Allen: https://www.youtube.com/channel/UCbTw29mcP12YlTt1EpUaVJw

### Structs vs Classes
- https://developer.apple.com/documentation/swift/choosing_between_structures_and_classes
Use structs as much as possible, but classes when you need reference or inheritance.

- you should never force unwrap optionals
- you should never use a for loop (use higher level functions map, filter and reduce)
- flatmap removes nils and converts optionals to non optionals!  neat.
- leave off self as much as possible


### Stuff I want to learn
- Hashable protocol 
- Sequence protocol: A type that provides sequential, iterated access to its elements. (the base or foundation of collections)
- Collection protocol: A sequence whose elements can be traversed multiple times, nondestructively, and accessed by an indexed subscript (inherits from Sequence)
- Bidirectional Collection:  A collection that supports backward as well as forward traversal.
- Other Protocols
- Optionals - it's just an enum with case some or none.
- Error Handling!
- Generics 


Iterators

After talking with my manager, we've talked about different ways for me to improve my development skillsets on my own.  Here are some of our ideas:
### Ideas for learning
- Implement new frameworks for fun
- Read the Docs!
  - https://developer.apple.com/documentation/swift
  - https://developer.apple.com/documentation/swift/swift_standard_library
  - https://developer.apple.com/documentation/swift/adopting_common_protocols
  - https://developer.apple.com/documentation/swift/preventing_timing_problems_when_using_closures
  - https://developer.apple.com/documentation/swift/swift_standard_library/collections/sequence_and_collection_protocols
- Look at Github projects and read implmentations
- Write a custom framework (Billboard)
- Publish custom framework to CocoaPods & Carthage
- Do more networking (Almofire)
- Do more NSOperations
- Use Firebase stuff more
- Convert internal Objective C frameworks into Swift
- Take courses
- Read Books/Tutorials
- Write Test!
- Watch YouTube Videos
- Watch WWDC Videos
  - https://developer.apple.com/videos/wwdc2018/
  - https://developer.apple.com/videos/wwdc2017/
  - https://developer.apple.com/videos/wwdc2016/
  - https://developer.apple.com/videos/wwdc2015/


### Specific WWDC Videos I want to watch: ✅


##### 2013
- https://developer.apple.com/videos/play/wwdc2013/502/  Introduction to Sprite Kit
- https://developer.apple.com/videos/play/wwdc2013/404/  ✅ Advances in Objective-C  
  - `#import` > Copy/paste text headers into .m files
  - `@import` > Imports module (which encapsulates a framework and is compiled separately)  Imports the API - Semantic import (doesn't need to parse headers.  Local macro definitions have no effect on framework API)
  - Submodules `@import iAd.ADBannerView;`  Similar to `#import <iAd/ADBannerView.h>`
  - Autolinking.  No need to manuallly "link binary with libraries" (I don't get this yet)
  - Xcode Automatically changes #import into @import now...  No code changes needed
  - how's it work?  Module Maps > Establish relationship between headers and modules.  Modules are cached in derived data.  Next time you import a module, it is already there.
  - `instancetype` vs `id` - A contextual keyword, only for return types.  Subclasses do not need to redeclare instance type methods.  The compiler contextually matches the return type to the receiver
  - Enums are/were essentailly global integers 


##### 2014
- https://developer.apple.com/videos/play/wwdc2014/228/  A Look Inside Presentation Controllers
- https://developer.apple.com/videos/play/wwdc2014/229/  Advanced iOS Application Architecture and Patterns
- https://developer.apple.com/videos/play/wwdc2014/236/  Building Interruptible and Responsive Interactions
- https://developer.apple.com/videos/play/wwdc2014/224/  Core iOS Application Architectural Patterns
- https://developer.apple.com/videos/play/wwdc2014/416/  Building Modern Frameworks
- https://developer.apple.com/videos/play/wwdc2014/406/  Integrating Swift with Objective-C


##### 2015
- https://developer.apple.com/videos/play/wwdc2015/401/  Swift and Objective-C Interoperability
- https://developer.apple.com/videos/play/wwdc2015/408/  Protocol-Oriented Programming in Swift
- https://developer.apple.com/videos/play/wwdc2015/231/  Cocoa Touch Best Practices
- https://developer.apple.com/videos/play/wwdc2015/218/  Mysteries of Auto Layout, Part 1
- https://developer.apple.com/videos/play/wwdc2015/219/  Mysteries of Auto Layout, Part 2
- https://developer.apple.com/videos/play/wwdc2015/202/  What's New in Cocoa
- https://developer.apple.com/videos/play/wwdc2015/405/  Authoring Rich Playgrounds
- https://developer.apple.com/videos/play/wwdc2015/403/  Improving Your Existing Apps with Swift
- https://developer.apple.com/videos/play/wwdc2015/711/  Networking with NSURLSession

##### 2016
- https://developer.apple.com/videos/play/wwdc2016/216/  Advances in UIKit Animations and Transitions
- https://developer.apple.com/videos/play/wwdc2016/225/  Extending Your Apps with SiriKit
- https://developer.apple.com/videos/play/wwdc2016/213/  Improving Existing Apps with Modern Best Practices
- https://developer.apple.com/videos/play/wwdc2016/236/  What's New in Auto Layout
- https://developer.apple.com/videos/play/wwdc2016/205/  What's New in Cocoa Touch
- https://developer.apple.com/videos/play/wwdc2016/419/  Protocol and Value Oriented Programming in UIKit Apps
- https://developer.apple.com/videos/play/wwdc2016/720/  Concurrent Programming With GCD in Swift 3
- https://developer.apple.com/videos/play/wwdc2016/705/  How iOS Security Really Works
- https://developer.apple.com/videos/play/wwdc2016/714/  Networking for the Modern Internet

##### 2017
- https://developer.apple.com/videos/play/wwdc2017/244/  Efficient Interactions with Frameworks
- https://developer.apple.com/videos/play/wwdc2017/414/  Engineering for Testability
- https://developer.apple.com/videos/play/wwdc2017/706/  Modernizing Grand Central Dispatch Usage
- https://developer.apple.com/videos/play/wwdc2017/416/  Teaching with Swift Playgrounds
- https://developer.apple.com/videos/play/wwdc2017/212/  What's New in Foundation
- https://developer.apple.com/videos/play/wwdc2017/818/  60 Second Prototyping
- https://developer.apple.com/videos/play/wwdc2017/230/  Advanced Animations with UIKit 

##### 2018
- https://developer.apple.com/videos/play/wwdc2018/402/  Getting the Most out of Playgrounds in Xcode
- https://developer.apple.com/videos/play/wwdc2018/223/  Embracing Algorithms
- https://developer.apple.com/videos/play/wwdc2018/406/  Swift Generics
- https://developer.apple.com/videos/play/wwdc2018/214/  Building for Voice with Siri Shortcuts
- https://developer.apple.com/videos/play/wwdc2018/220/  High Performance Auto Layout
- https://developer.apple.com/videos/play/wwdc2018/215/  Introducing ClassKit
- https://developer.apple.com/videos/play/wwdc2018/211/  Introduction to Siri Shortcuts
- https://developer.apple.com/videos/play/wwdc2018/235/  UIKit: Apps for Every Size and Shape


#### General Notes
- Set Algebra: Subtraction, Intersection, Union.  
- NSSet is like a dictionary without values.
- Options... `if let`, `??` ! `!`

#### Internal Frameworks I want to learn more about
- Whats New
- TubePlayer
- Planning Center Cache
- Random Image
- Upload Service
- Plannin Center Router
- Audio Player Cache
- MCT Audio Player
- Alert View
- Services Sidebar
- Document Store
- PCOKit
- PCOCocoa
  - Network Cache
  - Loper
  - Socket Rocket
  - Open Sky Operation
  - Planning Center Auth
  - MCT Object Store
  - MCT JSON

#### 3rd Party Frameworks We Use
- Zendesk
- 1Password
- Fabric
- Crashlytics
- React Native

#### External Frameworks I want to learn
- Snail:  https://github.com/UrbanCompass/Snail/
- SnapKit: https://github.com/SnapKit/SnapKit
- Realm: https://github.com/realm/realm-cocoa
- Firebase: https://firebase.google.com/docs/storage/ios/start
- Alamoefire: https://github.com/Alamofire/Alamofire
