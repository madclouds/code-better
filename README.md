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
- Iterators

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


### Specific WWDC Videos I want to watch: ✅ == watched


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
  - Design Information Flow (rather than letting it grow adhoc like a weed).
    - Where is "truth"?
    - Truth vs. derived values (like a cache and should be treated as such)
    - When new truth is created the relationship is asymetical. 
  - Define clear responsibilities 
    - dont duplicate code....... great advice...
  - Simplify with immutability
    - skipped over this part
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
- https://developer.apple.com/videos/play/wwdc2016/240/  Increase Usage of Your App With Proactive Suggestions

##### 2017
- https://developer.apple.com/videos/play/wwdc2017/244/  Efficient Interactions with Frameworks
- https://developer.apple.com/videos/play/wwdc2017/414/  Engineering for Testability
- https://developer.apple.com/videos/play/wwdc2017/706/  Modernizing Grand Central Dispatch Usage
- https://developer.apple.com/videos/play/wwdc2017/416/  Teaching with Swift Playgrounds
- https://developer.apple.com/videos/play/wwdc2017/212/  What's New in Foundation
- https://developer.apple.com/videos/play/wwdc2017/818/  ✅ 60 Second Prototyping
  - Use Keynote to prototype interactive apps.  Iterate fast to explore ideas and interactions. Neat.
- https://developer.apple.com/videos/play/wwdc2017/230/  Advanced Animations with UIKit 

##### 2018
- https://developer.apple.com/videos/play/wwdc2018/402/  Getting the Most out of Playgrounds in Xcode
- https://developer.apple.com/videos/play/wwdc2018/223/  Embracing Algorithms
  - Talks about different collection methods
  - Talked about different protocols
  
- https://developer.apple.com/videos/play/wwdc2018/406/  Swift Generics
- https://developer.apple.com/videos/play/wwdc2018/214/  Building for Voice with Siri Shortcuts
- https://developer.apple.com/videos/play/wwdc2018/220/  High Performance Auto Layout
- https://developer.apple.com/videos/play/wwdc2018/215/  Introducing ClassKit
- https://developer.apple.com/videos/play/wwdc2018/211/  ✅ Introduction to Siri Shortcuts
  - Define a shortcut for each action you want
    - Accelerate user to perform a key function of your app
    - Be of persistant interest to the user.  The user might want to do multiple times
    - Be executable at any time.  No state!
    - 2 APIs for supporting shortcuts:
      - NSUserActivity is a light weight way to let siri know
        - Opens something in your app
        - Represents showing items that you index in spotlight search of for handoff.
        - you use use this for lots of activities in your app so siri can offer better suggestions
        - Example:
          ```
          let activity = NSUserActivity(activityType: "com.AppCoda.SiriSortcuts.sayHi") // 1
          activity.title = "Say Hi" // 2
          activity.userInfo = ["speech" : "hi"] // 3
          activity.isEligibleForSearch = true // 4
          activity.isEligibleForPrediction = true // 5
          activity.persistentIdentifier = NSUserActivityPersistentIdentifier(rawValue: "com.AppCoda.SiriSortcuts.sayHi") // 6
          view.userActivity = activity // 7
          activity.becomeCurrent() // 8
          ```
      - Intents.  Siri has built in intents.  Custom intents!
  - Donate shortcut tell system every time the user does something in your app that you expose a shortcut for.  Lets siri learn when and where is the right time to sugest your shortcut.
    - Turn on debugging by going to Settings > Developer and enable `Display Recent Shortcuts` and `Display Donations on Lock Screen`
  - Handle shortcut when the user wants to use your shortcut, you need to be ready for your app or app extension to handle
- https://developer.apple.com/videos/play/wwdc2018/235/  UIKit: Apps for Every Size and Shape


#### General Notes
- Set Algebra: Subtraction, Intersection, Union.  
- NSSet is like a dictionary without values.
- Options... `if let`, `??` ! `!`

#### Internal Frameworks
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

#### 3rd Party Frameworks in PC
- Zendesk
- 1Password
- Fabric
- Crashlytics
- React Native

#### External Frameworks
- Snail:  https://github.com/UrbanCompass/Snail/
- SnapKit: https://github.com/SnapKit/SnapKit
- Realm: https://github.com/realm/realm-cocoa
- Firebase: https://firebase.google.com/docs/storage/ios/start
- Alamoefire: https://github.com/Alamofire/Alamofire

#### Apple Framework
- https://developer.apple.com/documentation

#### Security
- https://developer.apple.com/library/archive/documentation/Security/Conceptual/SecureCodingGuide/Introduction.html
- https://stackoverflow.com/questions/9448632/best-practices-for-ios-applications-security

#### More frameworks to review:
- https://github.com/matteocrippa/awesome-swift


## Mentor Notes
#### 11/16 @11am notes:
- Went throught frameworks at a high level.  Talked about core data.  Worked through an "offline" bug (https://trello.com/c/O4Bkmgsf/2448-478588-app-goes-offline-when-using-cell-data) together. started looking into the largest crash on fabric (http://crashes.to/s/0296d3aee8f).
- How do we get a nice pretty stack trace like Fabric in xcode?


## Notes for next Mentorship
- ~~Talk about sidebar blockout data grouping `NSArray <NSArray<PCOBlockout *> *> *blockouts`~~ Used a NSFetchedResultsController with a `sectionNameKeyPath`
- Talk about code compilation process.  Talk about what happens when you hit command+B, and when you archive.
- Talk about schedule conflicts and how to keep them out of the database, and use them in memory only. (check `BlockoutDeclineExistingPlansPickerController`)
- Review JSON mapping and Core Data interactions.  Talk about API call.
- Write more swift!


## Mentor Stuffs
- `PCOServicesCoreDataStack.m` uses `+ (BOOL)prepareCoreDataStack:(NSError **)error`.  What's the double `**` about.  I know `&error` is a reference pointer, but I don't know what `**` is.  Answer:  ** is a pointer to a pointer. Since functions in C take arguments by value, it means you can't change the value of the argument in that function. But, by providing a level of indirection and passing a pointer to the pointer, you can change the value.


## Mentor notes from 12/6
- Talked about writing swift in services with new controllers.  and use snapkit maybe for swift stuff.
- Try talking about implementation strategy with James before working on another big task.

## Questions for next session
- Review where state should be held for Household Filters (Notes in notebook)
### Talk about different
- Imparative programming
- Functional programming
- Object Oriented programming
- Inheritance-based programming
- Prototytpe-based programming
- Declarative programming

^ Relevant https://flutter.io/docs/resources/faq#what-programming-paradigm-does-flutters-framework-use

- Find a video to watch and discuss next time.

#### 1/2/2019 notes:
Got together to talk about blockout conflict implementation strategy found here: https://gist.github.com/madclouds/47e6edc3666cf963b73bbdc5f5e8ecf4

#### 1/3/2019 notes:
Watched video together - Embracing Algorithms - https://developer.apple.com/videos/play/wwdc2018/223/  
Learned about tripple slashes in Xcode `///` for documentation that's included in `.swiftdoc` and displayed within xcode.
Look through swift guides
Looked at big O notation and talked about the different complexities

#### Questions for next meeting:
- how often to git commit
- get rebase
- automated Test Flight build from github merge? - See if I can use CircleCI to automate build and deploy to Test Flight.  Search what other options are avaiable - git commit message checks the git message for a trigger words.

- GCC?  ([GNU Compiler Collection](https://gcc.gnu.org/onlinedocs/gcc/G_002b_002b-and-GCC.html#G_002b_002b-and-GCC)) 
    - https://useyourloaf.com/blog/compiler-options-in-xcode-gcc-or-llvm/
- `__unused` and `_Nullable` and other property identifiers - instead of `#pragma unused(param)`

##### Unit Testing
- Wrote some tests for MCTJSON JSONHelper class
- Write tests for any public interfaces!
##### Task to work on together
- What's the correct way to disable the header highlight in on a dashboard card based on data. (just an exercise)
#### Swift
- Any new file should be written in Swift

```[self.orderedHouseholdMembers filteredArrayUsingPredicate:[NSPredicate predicateWithBlock:^BOOL(id  _Nullable evaluatedObject, __unused NSDictionary<NSString *,id> * _Nullable bindings) {```


##### Becoming a better programmer
https://www.youtube.com/watch?v=85fXs6cQETQ
Models of learning:  http://pics.pco.bz/fc9ab0f1fb96

Try Fastlane for build automation.
https://docs.fastlane.tools/getting-started/ios/beta-deployment/

`NS` namespace belongs to NextStep, a company Apple bought and based MacOS/iOS on.  Example `NSObject`.
Start watching Core Data course:  https://classroom.udacity.com/courses/ud325

##### Course Notes
- Core Data - Data layer management framework
  - Data Structure, relationships, changing models and updating UI when models change.
  - Core Data is a framework/library/bundle of code
  - referential integrity - Core Data uses two-sided relationships.  Core Data traverses the web of entity class instances (object graph) and makes sure all affected references are updated.
  - Deleteion Rules:
    - Cascade: Deleteing a notebook will causes all of the notes to be deleted
    - Nullify means the relationship will simply be removed, but the referenced notebook remains
    
 - Faults - relationships are not immediately loaded. Instead, Core Data has a mechanism called faulting. Faulting allows any attribute or relationship to be in a special state where it is promised to load when needed. When you fetch a managed object, its relationships are initially represented as faults.
    
##### Core Data Stack
- 1 or more Managed Object Context(s)
  - Scratch pad to edit or update NSManagedObjects or create new ones
- Managed Object Model
  - Describes data structure and relationships - `.xcdatamodeld` file
- Persistent Store Coordinator
  - Connects to 1 or more persistant stores.  Translates store objects into managed objects, or managed objects into stored objects.
  - A mediator for turning persisted data into managed objects and turning managed objects into persisted data
- Persistent Container
  - set up the rest of stact
  - provie useful methods for working with contexts
  
- Core data migration.  `.xcmappingmodel`
  - automatic (light weight) vs custom
  - custom: subclass `NSEntityMigrationPolicy` and use `createDestinationInstances(forSource sInstance: NSManagedObject, in mapping: NSEntityMapping, manager: NSMigrationManager)`
  - Services doesn't use a migration/merge policy.  Instead builds the stack from scratch.
  
- Concurrency:
 - main queue vs private queue
 - Concurrency Types:
  - `NSPrivateQueueConcurrencyType`: Specifies that the context will be associated with a private dispatch queue
  - `NSMainQueueConcurrencyType`: Specifies that the context will be associated with the main queue.
 - Merge Policies
  ```
  NSErrorMergePolicyType
      Default policy for all managed object contexts.
      NSMergeByPropertyStoreTrumpMergePolicyType
      A policy that merges conflicts between the persistent store's version of the object and the current in-memory version by individual property, with the in-memory changes trumping external changes.
      NSMergeByPropertyObjectTrumpMergePolicyType
      A policy that merges conflicts between the persistent store's version of the object and the current in-memory version by individual property, with the external changes trumping in-memory changes.
      NSOverwriteMergePolicyType
      A policy that merges conflicts between the persistent store's version of the object and the current in-memory version by pushing the entire in-memory object to the persistent store.
      NSRollbackMergePolicyType
      A policy that merges conflicts between the persistent store's version of the object and the current in-memory version by discarding all state for the changed objects in conflict.
 ```
      
- `MCTObjectContext.m` line 291:

```
+ (NSDictionary *)defaultPersistentStoreOptions {
    return @{
             NSMigratePersistentStoresAutomaticallyOption: @YES,
             NSInferMappingModelAutomaticallyOption: @YES
             };
}
```
      
 - `NSPersistentContainer` iOS 10+ only - https://developer.apple.com/documentation/coredata/nspersistentcontainer?language=objc
 
 - Let's talk about Faulting!  https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CoreData/FaultingandUniquing.html

    
#### Transpose Quick View add Minor Support
 Talked with James about how to tackle this card:  https://trello.com/c/l4VQ5jVV
 Solution: https://gist.github.com/madclouds/8cc11aad8e7dc37660a3e4df515c0a49
    
    
--------

Check out this crash report together:  http://crashes.to/s/ac5c41cb64c

Review this together:  https://codesigning.guide/


Check out this together:  https://github.com/fastlane/examples

#### Can't get fastlane working for Services
#### Output:

```
▸ Signing /Users/erikbye/Library/Developer/Xcode/DerivedData/Services-awpfsigwemreoghcurxsonpypbpz/Build/Intermediates.noindex/ArchiveIntermediates/Services/InstallationBuildProductsLocation/Applications/Services.app
▸ Touching Services.app.dSYM
▸ Archive Succeeded
[16:11:20]: Exit status: 1

+---------------+-------------------------+
|            Build environment            |
+---------------+-------------------------+
| xcode_path    | /Applications/Xcode.app |
| gym_version   | 2.115.0                 |
| export_method | app-store               |
| sdk           | iPhoneOS12.1.sdk        |
+---------------+-------------------------+

[16:11:20]: ▸ Check dependencies
[16:11:20]: ▸ Code Signing Error: No profiles for 'com.ministrycentered.PlanningCenter.ServicesSchedule' were found:  Xcode couldn't find any iOS App Development provisioning profiles matching 'com.ministrycentered.PlanningCenter.ServicesSchedule'. Automatic signing is disabled and unable to generate a profile. To enable automatic signing, pass -allowProvisioningUpdates to xcodebuild.
[16:11:20]: ▸ Swift 3 mode has been deprecated and will be removed in a later version of Xcode. Please migrate "Services Schedule" to Swift 4.2 using "Convert > To Current Swift Syntax…" in the Edit menu.
[16:11:20]: ▸ Swift 3 mode has been deprecated and will be removed in a later version of Xcode. Please migrate "Services Schedule" to Swift 4.2 using "Convert > To Current Swift Syntax…" in the Edit menu.
[16:11:20]: ▸ Code Signing Error: Code signing is required for product type 'App Extension' in SDK 'iOS 12.1'
[16:11:20]: 
[16:11:20]: ⬆️  Check out the few lines of raw `xcodebuild` output above for potential hints on how to solve this error
[16:11:20]: 📋  For the complete and more detailed error log, check the full log at:
[16:11:20]: 📋  /Users/erikbye/Library/Logs/gym/Services-Services.log
[16:11:20]: 
[16:11:20]: Looks like fastlane ran into a build/archive error with your project
[16:11:20]: It's hard to tell what's causing the error, so we wrote some guides on how
[16:11:20]: to troubleshoot build and signing issues: https://docs.fastlane.tools/codesigning/getting-started/
[16:11:20]: Before submitting an issue on GitHub, please follow the guide above and make
[16:11:20]: sure your project is set up correctly.
[16:11:20]: fastlane uses `xcodebuild` commands to generate your binary, you can see the
[16:11:20]: the full commands printed out in yellow in the above log.
[16:11:20]: Make sure to inspect the output above, as usually you'll find more error information there
```

#### Fixed! ^
- Needed to manually set the profiles to the ones generated by fastlane's Match service.

#### Design Patterns!
- I want to get better at them.  I want to talk about them and better understand how and why to use them.  I know all the terms needed to program, but I don't use them often enough to combine all the pieces together.

- Talk about push notification bug together.  Pair Programming!

