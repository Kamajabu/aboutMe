# aboutMe
About me and my projects


**Table of Contents**

[TOC]

# iOS

## BitBayWatcher (iOS + watchOS)
***08.2019 – 09.2019***

Application for watching current offers posted on BitBay market, focused on quick access to information presented on Apple Watch, and configured from iPhone parent application.

Among most interesting features, there are:
- WatchConnectivity allowing adding watched currencies from iPhone, which modifies items displayed on AppleWatch,
- Managing and restoring state between session, default state for first run included,
- MVVM architecure, view models unit tested,
- Network layer and data managent based on reactive streams, eg. auto update and displaying remaining time (count down included) until next data fetch,
- Use of generics, protocols, default implementations, shared ViewModels and Models - reducing redundancy between phone and watch layers.

Libs I've used through the development process (CocoaPods): 
- RxSwift,
- RxCocoa,
- Firebase/Analytics,
- Fabric,
- Crashlytics.

## Aviation related project (Details Restricted)
***03.2018 – 09.2019***

For a year and a half I was working on aviation related projects, among other things, I:
- Worked with international team of developers on project related to aviation industry,
- Closely cooperated with product owners, testers and other programmers in agile process of creating software from idea to client delivery, divided into 2 weeks sprints,
- Taken a part in ongoing process of improving code base, by refactoring and adapting architecture based on continuously changing requirements,
- Conducted a workshops and presentations about reactive programming.
- Made over 2k commits, 500 Pull Requests, and added almost 200k lines of code.

## Kupie.se 
***01.2017 – 06.2017***

Mobile app (iOS) for website kupie.se. 

The main goal of the application is to save the web pages containing products we would like to have. It's like pocket app for shopping.

I've designed app, was responsible for UX and development. Among my tasks were:
- Designing and implementing registration and login screens, validating input data, extended by animated actions guiding user to which fields required his attention - using set of additional animation libraries eg. Spring,
- Integrating with Facebook SDK (registration, login, share etc.),
- Network communication (with jsonapi standard) using Moya - Alamofire,
- Mapping data structures with ObjectMapper,
- Focusing on reactive approach in data management using RxSwift,
- Managing fetching and catching product images with Nuke,
- Projecting and creating design consistent with iOS Human Interface Guidelines,
- Deploying an app on AppStore,
- Integrating crashlytics for real time crash and bug reports,
- Integrating Fabric for simple app distribution directly to clients and testers device,
- Creating unit tests using dedicated libraries - Quick, Nimble, MockingJay,
- Creating multiple language versions,
- Implementing architectures patterns accordingly to complexity of code, mostly MVC/MVP,
- Creating realtime websocket communication for updating product status using Starscream library,
- Creating extension for adding gift (capturing and sending link, updating list etc.) directly from browser (Safari),
- Reducing boilerplate code and maximizing code transparency using SwiftLint.

Libs I've used through the development process: 
- Fabric,
- Crashlitics,
- SwiftLint,
- SwiftyJSON,
- Alamofire,
- Nuke,
- RxCocoa,
- Moya,
- ObjectMapper,
- RxSwift,
- RxOptional,
- RxDataSources,
- Starscream,
- FBSDKCoreKit,
- FBSDKShareKit (FacebookShare),
- FBSDKLoginKit,
- SCLAlertView,
- Quick,
- Nimble,
- Mockingjay.

# Android
## Kupie.se 
***06.2016 – 12.2016***

Mobile app (Android) for website kupie.se. 

The main goal of the application is to save the web pages containing products we would like to have. It's like pocket app for shopping.

I've designed app, was responsible for UX and development. Among my tasks were:
- integrating with Facebook SDK (login, share etc.),
- integrating with Twitter SDK (share),
- Network communication (with jsonapi standard) using Retrofit and RxJava,
- Managing fetching and catching product images with Glide,
- Projecting and creating design consistent with Material Design,
- Deploying an app on Google Play and managing beta process,
- Integrating crashlytics for real time crash and bug reports,
- Creating unit and instrumental tests,
- Creating multiple language versions,
- Implementing MVP architecture using dependency injection,
- Creating websocket communication for updating product status,
- Reducing boilerplate code and maximizing code transparency,
- Adding and editing user avatars (both from camera and gallery).

Libs I've used through the development process: 
- RxAndroid,
- Retrofit,
- Nv websocket client,
- Glide,
- Dagger2,
- Lombok,
- ImagePick,
- ImageCropper,
- ButterKnife,
- EventBus,
- Google Places API,
- Google Maps API,
- Facebook SDK
- Mockito & PowerMock,
- JUnit,
- Robolectric,
- Espresso.

## I Hate Space - Action mobile game

***01.2016***

I've created an Android game and posted it in the Google Play store. The game was created using the libgdx framework. This is a fully code-based solution, with no additional editors. Thanks to that approach, I've learned how the algorithms responsible for game play work and how to optimize applications, how to manage graphics modules and much more. I also worked with advertising networks such as AdMob, StartApp, Chartboost. I tested the application and designed the UX myself.

## AttApp 

University project for selecting nearby attractions based on user preferences.

Among my tasks were:
- Detecting user localization,
- integrating google localization API(with build-in module),
- fetching nearby places data in JSON format using retrofit (omitting build-in module),
- Displaying to user nearby places according to his choices,
- Using Analytic Hierarchy Process and Promethee Algorithms for choosing best place to for user according to his preferences,
- Designing and implementing multi-table interface using fragments.


