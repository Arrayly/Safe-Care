### Android app starter template


## About

SafeCare is a nursing documentation software that allows nurses to record all patient documentation digitally as opposed to the traditional paper format. In doing so, SafeCare removes the nursing ‘audit’ task, saving 104,000e per nursing home per year.


## Business Objectives
* Speed up documentation time for nurses by 60%
* Remove the need for nurses to audit nursing homes. In turn saving 2,000e per nursing home per week
* Increase quality and regulation compliance


Patient List             |  Live Audit       |      Daily Tasks
:-------------------------:|:-------------------------:|:-------------------------:
![Screenshot_1](https://user-images.githubusercontent.com/57268763/79758913-e9e6f280-8315-11ea-8774-ec8c847b4fff.png)  |  !
![Screenshot_4](https://user-images.githubusercontent.com/57268763/79761526-7e068900-8319-11ea-9426-6f976ac9239e.png)  |  ![Screenshot_3](https://user-images.githubusercontent.com/57268763/79759693-eacc5400-8316-11ea-9431-78826ab1a318.png)


## Features
- Clean architecture with 3 layers
    - Data (for models, database, API and preferences)
    - Domain (for business logic)
    - Presentation (for UI logic, with MVVM)
- Tests
    - Unit tests
    - Application tests
    - Activity tests (with [Espresso](https://google.github.io/android-testing-support-library/docs/espresso/))
    - Application has a testing flag
- Dependency injection (with [Dagger v2](http://google.github.io/dagger/))
- View injection (with [Butterknife](http://jakewharton.github.io/butterknife/))
- Reactive programming with RxJava 2 and RxAndroid
- Preconditions
- Google Design library
- Android architecture components to share ViewModels during configuration changes
- Logging (with [Timber](https://github.com/JakeWharton/timber))
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

