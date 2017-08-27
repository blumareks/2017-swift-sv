
<img src="https://farm5.staticflickr.com/4337/36010504144_e7fdf1c8e0_z.jpg">

# Learn to build Cognitive apps with Watson services & Swift on the Server
This is a repo for Swift on the Server Workshop in San Francisco/Silicon Valley in 2017. If you use it please give me a star - thank you!

## Background to the Swift Language

<img src="https://farm5.staticflickr.com/4389/36674479412_fab6b1f1ed.jpg">[https://console.bluemix.net/]

[The Swift Language](https://en.wikipedia.org/wiki/Swift_(programming_language))

[A Swift Tour](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1)

[Swift Language Guide](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309)

## Preparation
Please start by signing up for Bluemix: [Bluemix.net](http://bluemix.net) (the access to the services for a trial account is free of charge for 30 days for development purposes only). There is also a [Lite account](https://www.ibm.com/cloud-computing/bluemix/standard-account)

<img src="https://farm5.staticflickr.com/4406/36674633642_e1e0526d7c.jpg">[https://console.bluemix.net/]
<img src="https://farm5.staticflickr.com/4356/36674633612_4af6e3a0e5.jpg">[https://console.bluemix.net/]

Download CLI for Cloudfoundry - [CF CLI](https://github.com/cloudfoundry/cli/releases/) You run this command on your computer to interact with apps you are creating in the IBM Bluemix Cloud.

## Lab 1 Introduction to Swift on the Server
<img src="https://farm5.staticflickr.com/4431/36449211700_2637512c4c.jpg">
Lab 1a): Check out the [Swift Sandbox](https://swift.sandbox.bluemix.net/) 

[Let's look at the Kitura code](https://github.com/IBM-Swift/Kitura)


followed by [Swift Package Catalog](https://packagecatalog.com/) 

<img src="https://farm5.staticflickr.com/4372/36449336690_46a784a18c.jpg">

Lab 1b): Launch Swift on the Server on the IBM Cloud. [the Swift service for Kitura](https://console.bluemix.net/catalog/starters/runtime-for-swift?env_id=ibm%3Ayp%3Aus-south&taxonomyNavigation=apps)

## (Optional) local Swift Server (IBM Kitura)
If you have a Mac with the Xcode 8.3.+ follow this: [kitura.io](http://www.kitura.io/)

## IBM Developer Journeys with Server Side Swift
[IBM has created a set of Developer Journeys for developers to help them create various applications/](https://developer.ibm.com/code/journey/category/swift-on-the-server/)

## Lab 2 Use Swift to interpret unstructured data from Hacker News
[Run the originsal YCombinator Hackernews here](https://news.ycombinator.com/)

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







## Stretch goal: For Lab 3, select one of three Developer Journeys below:
1) [Build a Swift-based mobile chatbot to provide recommendations, reservations, and event planning/](https://developer.ibm.com/code/journey/build-a-cognitive-recommendation-app-with-swift/), or 
2) [Build and deploy an enterprise Swift application that uses multiple services and libraries](https://developer.ibm.com/code/journey/build-an-enterprise-swift-app-using-services/), or 
3) [Smart picture sharing on the go/](https://developer.ibm.com/code/journey/apply-cognitive-to-mobile-images-on-the-go/)

Thank you for using it. Follow us on Twitter:
[@blumareks](https://twitter.com/blumareks) & [@USABloggen](https://twitter.com/USABloggen)
