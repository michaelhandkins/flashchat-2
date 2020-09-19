# Flash-Chat

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. Firebase Authentication is used for creating and validating user accounts, and Firebase Firestore is used as a backend database to store and retrieve messages from the cloud. 

## This App Demonstrates...

* How to integrate third party libraries using Cocoapods and Swift Package Manager.
* How to store data in the cloud using Firebase Firestore.
* How to query and sort the Firebase database.
* How to use Firebase for user authentication, registration and login.
* How to work with UITableViews and how to set their data sources and delegates.
* How to create custom views using .xib files to modify native design components.
* How to embed View Controllers in a Navigation Controller and understand the navigation stack.
* How to create a constants file and use static properties to store Strings and other constants.
* How to create animations using loops.
* The App Lifecycle and how to use viewWillAppear or viewWillDisappear.
* How to create direct Segues for navigation.

## User Interface

Upon launching the app, users will be greeted with an animation of the app's title.

![](https://github.com/michaelhandkins/flashchat-2/blob/master/animation.gif)

By tapping "register", the user can then get signed up for their own account on Flashchat. If the registration is successful, they will then be escorted to the messaging screen.

![](https://github.com/michaelhandkins/flashchat-2/blob/master/flashchat_register.gif)

Registered users can sign-in using the "Log In" button. Once signed in, they can send and receive messages to and from other registered users.

![](https://github.com/michaelhandkins/flashchat-2/blob/master/sign_in.gif)

If there are any errors with the sign-in or registration process, users will receive a pop-up that describes the error.

![](https://github.com/michaelhandkins/flashchat-2/blob/master/error.gif)
