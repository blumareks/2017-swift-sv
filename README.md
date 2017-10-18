
<img src="https://farm5.staticflickr.com/4337/36010504144_e7fdf1c8e0_z.jpg">

# Learn to build Cognitive apps with Watson services & Swift on the Server
This is a repo for Swift on the Server Workshop in San Francisco/Silicon Valley in 2017. If you use it please give me a star - thank you!

# Use this link to open this page: ibm.biz/2017-server-side-swift-sv

## Background to the Swift Language

<img src="https://farm5.staticflickr.com/4389/36674479412_fab6b1f1ed.jpg">

[The Swift Language](https://en.wikipedia.org/wiki/Swift_(programming_language))

[A Swift Tour](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1)

[Swift Language Guide](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309)

## Preparation
Please start by signing up for [Bluemix](http://ibm.biz/buildapp082917) (the access to the services for a trial account is free of charge for 30 days for development purposes only). There is also a [Lite account](https://www.ibm.com/cloud-computing/bluemix/standard-account)

[<img src="https://farm5.staticflickr.com/4406/36674633642_e1e0526d7c.jpg">](https://console.bluemix.net/)

[<img src="https://farm5.staticflickr.com/4356/36674633612_4af6e3a0e5.jpg">](https://console.bluemix.net/)

Download CLI for Cloudfoundry - [CF CLI](https://github.com/cloudfoundry/cli/releases/) You run this command on your computer to interact with apps you are creating in the IBM Bluemix Cloud.

## Lab 1 Introduction to Swift on the Server

[Lab 1A: Check out the Swift Sandbox](https://swift.sandbox.bluemix.net/) 

<img src="https://farm5.staticflickr.com/4431/36449211700_2637512c4c.jpg">

[Lab 1B: Check out the Swift Package Catalog](https://packagecatalog.com/) 

<img src="https://farm5.staticflickr.com/4372/36449336690_46a784a18c.jpg">

[Lab 1C: create the Swift service for Kitura in the IBM Cloud](https://console.bluemix.net/catalog/starters/runtime-for-swift)

<img src="https://farm5.staticflickr.com/4394/36039596383_21dbf0765f.jpg">

[Let's look at the Kitura code](https://github.com/IBM-Swift/Kitura) , [and at the Kitura Homepage](http://www.kitura.io/)

## Running Server from IBM Cloud - overview
[Let's run the Swift service for Kitura in the IBM Cloud](https://lennart-kitura-galvanize.mybluemix.net/)

# Hands-on - Marek
## (Optional) local Swift Server (IBM Kitura)
If you have a Mac with the Xcode 8.3.+ follow this: [kitura.io](http://www.kitura.io/)

The changes with *for Swift4.0 / Xcode 9.0* vs the original description for Swift 3 at kitura.io to be included in ```Package.swift``` : 
```swift
// swift-tools-version:4.0
// The swift-tools-version declares the minimum version of Swift required to build this package.

import PackageDescription

let package = Package(
    name: "mytest",
    dependencies: [
        // Dependencies declare other packages that this package depends on.
        // .package(url: /* package url */, from: "1.0.0"),
        .package(url: "https://github.com/IBM-Swift/Kitura.git", from: "1.7.0")
        ],
    targets: [
        // Targets are the basic building blocks of a package. A target can define a module or a test suite.
        // Targets can depend on other targets in this package, and on products in packages which this package depends on.
        .target(
            name: "mytest",
            dependencies: ["Kitura"]),
    ]
)
```

launch the app with: ```.build/x86_64-apple-macosx10.10/debug/mytest```

## Running Server from IBM Cloud - overview
[Let's run the Swift service for Kitura in the IBM Cloud](https://lennart-kitura-galvanize.mybluemix.net/)

# Journeys - Lennart

## IBM Developer Journeys with Server Side Swift
[IBM has created a set of Developer Journeys for developers to help them create various applications/](https://developer.ibm.com/code/journey/category/swift-on-the-server/)

## Lab 2 Use Swift to interpret unstructured data from Hacker News
[Run the originsal Y Combinator Hackernews here](https://news.ycombinator.com/)

[Run the Watson-enabled Hacker News app here](http://lennart-hackernews-nlu-baffling-bandsman.mybluemix.net/)

We will use one of the Developer Journeys for this exercise: [Use Swift to interpret unstructured data from Hacker News](https://developer.ibm.com/code/journey/use-swift-interpret-unstructured-data-hacker-news/).

<img src="https://farm5.staticflickr.com/4376/36036955253_7d27aeda85.jpg">

[Let's start with the Github repository](https://github.com/IBM/Hackernews-NLU)

In the GitHub repo we can either use the magical Big Blue Deploy to Bluemix button or else deploy the Hackernews-NLU app to Bluemix step by step.

Whichever method you use please take he opportunity to check out how your code looks in the Bluemix console (see below)

<img src="https://farm5.staticflickr.com/4399/36676475452_4b398b2fd7.jpg">


### A Look at the Swift Code

[Main.swift](https://github.com/IBM/Hackernews-NLU/blob/master/Sources/main.swift)

[Newsarticles.swift](https://github.com/IBM/Hackernews-NLU/blob/master/Sources/NewsArticles.swift)

[Controller.swift](https://github.com/IBM/Hackernews-NLU/blob/master/Sources/Controller.swift)

## Stretch goal: For Lab 3, select one of the three Developer Journeys below:
1) [Build a Swift-based mobile chatbot to provide recommendations, reservations, and event planning/](https://developer.ibm.com/code/journey/build-a-cognitive-recommendation-app-with-swift/), or 
2) [Build and deploy an enterprise Swift application that uses multiple services and libraries](https://developer.ibm.com/code/journey/build-an-enterprise-swift-app-using-services/), or 
3) [Smart picture sharing on the go/](https://developer.ibm.com/code/journey/apply-cognitive-to-mobile-images-on-the-go/)

## Survery
Did you like this workshop? Share with us your opinion and help us make it better! Please find the link for the survey: [ibm.biz/yourfeedback](http://ibm.biz/yourfeedback)

Thank you for using it. Follow us on Twitter:
[@blumareks](https://twitter.com/blumareks) & [@USABloggen](https://twitter.com/USABloggen)
