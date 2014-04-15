Mobile Continuous Integration
===========================
Here's an overview of tools we find useful for supporting our mobile continuous integration build process.

### General
* [Jenkins] (http://jenkins-ci.org/)
* [Cobertura Jenkins Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/Cobertura+Plugin) - Jenkins plugin that will reports code coverage
* [PMD Jenkins Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/PMD+Plugin) - Jenkins plugin that reports OCLint output in Jenkins
* [Travis CI] (https://travis-ci.org/) - Alternative to Jenkins for continuous integration
* [Gerrit] (https://code.google.com/p/gerrit/) - Tool to manage code reviews, integrates with Git
* [Git] (http://git-scm.com/) - Version management software
* [node.js] (http://nodejs.org/) - JavaScript on the server side, we use it for easily create fixture data for our apps.
* [Dashing] (http://shopify.github.io/dashing/) - Framework to create Dashboards - we use it to show our jenkins build results.
* [Etsy’s Journey to Continuous Integration for Mobile Apps] (http://codeascraft.com/2014/02/28/etsys-journey-to-continuous-integration-for-mobile-apps/) - Great blog writeup on Etsy's continuous integration journey.
* [TestFlight] (http://testflightapp.com/) - Service that assists with over-the-air distribution of native apps for testing
* [HockeyApp] (http://hockeyapp.net/features/) - Alternative to TestFlight for assisting with over-the-air distribution of native apps for testing

### iOS
* [OCLint] (http://oclint.org/) - Static code analyzer for Objective-C
* [OCMock] (http://ocmock.org/) - Mock object framework for Objective-C
* [CocoaPods] (http://cocoapods.org/) - Dependency manager for Objective-C projects
* [XCode Build Server] (https://developer.apple.com/library/ios/documentation/IDEs/Conceptual/xcode_guide-continuous_integration/000-About_Continuous_Integration/about_continuous_integration.html) - Apple's alternative to Jenkins
* [xctool] (https://github.com/facebook/xctool) - A 3rd party alternative to xcodebuild for command line builds of iOS apps
* [Xcode Overview: Unit Test Your App] (https://developer.apple.com/library/ios/documentation/ToolsLanguages/Conceptual/Xcode_Overview/UnitTestYourApp/UnitTestYourApp.html) - Overview of unit testing within Xcode
* [UIAutomation] (https://developer.apple.com/library/mac/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/UsingtheAutomationInstrument/UsingtheAutomationInstrument.html) - Testing framework provided by Apple for automating "interface tests" (aka integration tests)
* [Kiwi] (https://github.com/allending/Kiwi) - Behavior Driven Development framework for iOS
* [Frank] (https://github.com/moredip/Frank) - "Selenium for native iOS apps"
* [KIF] (https://github.com/kif-framework/KIF) - 3rd party, open source, ntegration testing framework for iOS

### Android

* [Android Studio](http://developer.android.com/sdk/installing/studio.html) - Android Studio is a new Android development environment based on IntelliJ IDEA.
* [Maven](http://maven.apache.org/) - Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.
* [Gradle](http://www.gradle.org/) - Gradle is build automation *evolved*.
* [Genymotion](http://www.genymotion.com/) - Genymotion is a super fast alternative to the Android Emulator that is provided with the Android SDK.
* [Robolectric](http://robolectric.org/) - A unit test framework that de-fangs the Android SDK jar so you can test-drive the development of your Android app. Tests run inside the JVM on your workstation in seconds.
* [Mockito](https://code.google.com/p/mockito/) - A mocking framework that lets you write beautiful tests that produce clean verification errors with clean & simple API.
* [Spoon](https://github.com/square/spoon) - Spoon aims to simplify automated ui testing by distributing instrumentation test execution and displaying the results in a meaningful way.
* [android-test-kit](https://code.google.com/p/android-test-kit/)
    * [Espresso](https://code.google.com/p/android-test-kit/wiki/Espresso) - A simple API for writing reliable UI tests.
    * [GoogleInstrumentationTestRunner](https://code.google.com/p/android-test-kit/wiki/GoogleInstrumentationTestRunner) - an improved InstrumentationTestRunner
* [Monkey](https://developer.android.com/tools/help/monkey.html) - Executes a pseudo-random stream of events (clicks, touches, gestures) against the app you are developing running on an emulator or a real device.
* [MonkeyRunner](https://developer.android.com/tools/help/monkeyrunner_concepts.html) - Allows you to write a Python program that installs an Android application or test package, runs it, sends keystrokes to it, takes screenshots of its user interface, and stores screenshots on the workstation.
* [uiautomator](https://developer.android.com/tools/help/uiautomator/index.html) - The uiautomator testing framework lets you test your user interface (UI) efficiently by creating automated functional UI testcases that can be run against your app on one or more devices.
