## Introduction

**React Native Firebase** makes using [Firebase](http://firebase.com) with React Native simple. It provides a _light-weight_ layer on-top of the native Firebase SDKs (iOS & Android) whilst mirroring the Firebase Web SDKs API as closely as possible.

## Why 

Although some features from the [Firebase Web SDK](https://www.npmjs.com/package/firebase) will generally work with React Native, it is mainly built for the web and as such has a limited compatible feature set.

In contrast we use the Firebase Native SDKs - this allows us to provide APIs to a vast majority of Firebase products and services.

See the [Supported Firebase Features](#Supported-Firebase-Features) table below to compare our supported features.

## Getting Started

We provide several options for you to get started with React Native Firebase, select a method from the table below that matches your requirements:

|  | Manual Integration  | Free Starter Kit | Premium Starter Kits |
|:---:|:-------------------:|:-----------------:|:--------------------:|
|  | [![manual][manual]](version /installation/initial-setup) | [![basic][basic]](version /installation/basic-kit) | [![premium][premium]](/kits) |
|  | Manually integrate React Native Firebase into your project by following our Android and iOS setup guides. | We've installed React Native Firebase into the standard React Native template app with only minimal steps for you to get going.      | Don't want to start from scratch? Use one of our premium starter kits to kick start development for your next app. |
|  | Recommended for **experienced** React Native **developers** and **existing** React Native **projects**. | Recommended for **beginners** and **new** React Native **projects**. | Recommended for **beginners** and **new** React Native **projects**. |
|  | [![continue][btn-guide]](version /installation/initial-setup) | [![btn-kit][btn-kit]](version /installation/basic-kit) | [![btn-kits][btn-kits]](/kits) |


## Supported Firebase Features
> The Web SDK column indicates what modules/functionality from the Web SDK are usable within React Native. A '**?**' indicates partial support.

| Firebase Features          | v2.2.x | v3.3.x | v4.1.x | Web SDK |
| -------------------------- | :----: | :----: | :----: | :-----: |
| **AdMob**                  |   ✅   |   ✅   |   ✅   |   ❌   |
| **Analytics**              |   ✅   |   ✅   |   ✅   |   ❌   |
| **App Indexing**           |   ❌   |   ❌   |   ❌   |   ❌   |
| **Authentication**         |   ✅   |   ✅   |   ✅   |   ✅   |
| _-- Phone Auth_            |   ❌   |   ✅   |   ✅   |   ❌   |
| **Core**                   | **?**  |   ✅   |   ✅   |   ✅   |
|  _-- Multiple Apps_        |   ❌   |   ✅   |   ✅   |   ✅   |
| **Cloud Firestore**        |   ❌   |   ✅   |   ✅   | **?**  |
| **Cloud Messaging (FCM)**  | **?**  | **?** |   ✅   |   ❌   |
| **Crashlytics**            |   ❌   |   ✅   |   ✅   |   ❌   |
| **Crash Reporting**        |   ✅   |   ✅   |   ✅   |   ❌   |
| **Dynamic Links**          |   ❌   |   ✅   |   ✅   |   ❌   |
| **[Functions Callable](https://firebase.googleblog.com/2018/04/launching-cloud-functions-for-firebase-1-0.html?m=1)**              |   ❌   |   ❌   |   ✅   |   ✅   |
| **Invites**                |   ❌   |   ❌   |   ✅   |   ❌   |
| **Instance ID**            |   ❌   |   ❌   | **?**  |   ❌   |
| **Performance Monitoring** |   ✅   |   ✅   |   ✅   |   ❌   |
| **Realtime Database**      |   ✅   |   ✅   |   ✅   |   ✅   |
| _-- Offline Persistence_   |   ✅   |   ✅   |   ✅   | **?**  |
| **Remote Config**          |   ✅   |   ✅   |   ✅   |   ❌   |
| **Storage**                |   ✅   |   ✅   |   ✅   | **?**  |


### Supported versions - React Native / Firebase

> The table below shows the supported versions of React Native and the Firebase SDKs for different versions of `react-native-firebase`

|                        | 2.2.x    | 3.3.x    |  4.0.x   |  **4.1.x**  |   4.2.x  |
|------------------------|----------|----------|----------|----------|----------|
| React Native           | 0.47 +   | 0.50 +   | 0.52 +   | 0.52 +   |  0.52 +  |
| Firebase Android SDK   | 11.0.0 + | 11.8.0 + | 12.0.0 + | 15.0.0 + | 15.0.0 + |
| Firebase iOS SDK       | 4.0.0 +  | 4.7.0 +  | 4.11.0 + | 4.11.0 + |  5.0.0 + |


## Questions

For questions and support please use our [Discord chat](https://discord.gg/C9aK28N) or [Stack Overflow](https://stackoverflow.com/questions/tagged/react-native-firebase). The issue list of this repo is **exclusively** for bug reports.

## Issues

Please make sure to complete the issue template before opening an issue. Issues not conforming to the guidelines may be closed immediately.

## Feature Requests

For feature requests please use our [Canny Board](http://invertase.link/requests).

## Changelog

Detailed changes for each release are documented in the [releases notes](https://github.com/invertase/react-native-firebase/releases).

## Contributing

Please make sure to read the [Contributing Guide](https://github.com/invertase/react-native-firebase/blob/master/CONTRIBUTING.md) before making a pull request.

Thank you to all the people who have already contributed to React Native Firebase!

<a href="graphs/contributors"><img src="https://opencollective.com/react-native-firebase/contributors.svg?width=890" /></a>

<hr>

[manual]: https://rnfirebase.io/static/media/docs-vector.cb67f7d6.png "Recommended for experienced React Native developers and existing React Native projects."
[basic]: https://rnfirebase.io/static/media/starter-project-vector.e45d010a.png "Recommended for beginners and new React Native projects."
[premium]: https://rnfirebase.io/static/media/premium-kits-vector.dc0245df.png "Recommended for beginners and new React Native projects."
[btn-guide]: https://i.imgur.com/Tmp5hku.png "View the integration guide"
[btn-kit]: https://i.imgur.com/N7GUGXo.png "Go to the basic starter kit repo"
[btn-kits]: https://i.imgur.com/1rmzlpV.png "Go to the basic starter kit repo"
