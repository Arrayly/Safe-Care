### Safe Care Digital Auditing App


## About

SafeCare is a nursing documentation software that allows nurses to record all patient documentation digitally as opposed to the traditional paper format. In doing so, SafeCare removes the nursing ‘audit’ task, saving 104,000e per nursing home per year.


## Business Objectives 🎯
* Speed up documentation time for nurses by 60%
* Remove the need for nurses to audit nursing homes. In turn saving 2,000e per nursing home per week
* Increase quality and regulation compliance

Patient List             |  Live Auditing          | Daily Tasks
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/57268763/79762207-59f77780-831a-11ea-8d14-9640dd274f9d.png)  |  ![](https://user-images.githubusercontent.com/57268763/79761526-7e068900-8319-11ea-9426-6f976ac9239e.png) | ![Screenshot_3](https://user-images.githubusercontent.com/57268763/79762569-d2f6cf00-831a-11ea-8379-0681b5083d36.png)



## Features
- Clean architecture with 3 layers
    - Data (for models, database, and preferences)
    - Domain (for business logic)
    - Presentation (for UI logic, with MVVM)
- Dependency injection (with [Dagger v2](http://google.github.io/dagger/))
- View binding (with [Data Binding Library](https://developer.android.com/topic/libraries/data-binding))
- Background tasks with kotlin Coroutines
- Material Design (with [Material Components](https://github.com/material-components/material-components-android))
- Android architecture components to share ViewModels during configuration changes
- Resource defaults
    - styles.xml
    - dimens.xml
    - colors.xml

## Getting started

1. Download this repository and open it on Android Studio
1. Rename the app package `io.bloco.template`
1. On `AndroidApplication.java`, change the package on the `checkTestMode` method
1. On `app/build.gradle`, change the applicationId to the new app package
1. On `app/build.gradle`, update the dependencies Android Studio suggests
1. On `string.xml`, set your application name 
1. On `colors.xml`, set your application primary and secondary colors 

And you're ready to start working on your new app.

## Notes

- Make sure the method `checkTestMode` inside `AndroidApplication` includes a test class
  that exists

## To Do

- Analytics (Google Analytics and Answers, at least)
- Crashlytics
- SharedPreferences helper with RxPreferences

