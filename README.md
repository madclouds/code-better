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
