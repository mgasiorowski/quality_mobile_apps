# Quality in mobile apps mindmap

Pull requests welcome

Table of Contents
=================

* [Table of Contents](#table-of-contents)
  * [Mindmap](#mindmap)
  * [Legend](#legend)
  * [Accessibility](#accessibility)
     * [Android](#android)
        * [Tools](#tools)
     * [iOS](#ios)
  * [Developer settings](#developer-settings)
     * [Android](#android-1)
  * [Debug](#debug)
     * [Android](#android-2)
  * [Reverse engineering](#reverse-engineering)
     * [Android](#android-3)
  * [Screen mirroring](#screen-mirroring)
     * [Android](#android-4)
     * [iOS](#ios-1)
  * [Emulator/simulator](#emulatorsimulator)
     * [Android](#android-5)
     * [iOS](#ios-2)
  * [Manual testing](#manual-testing)
  * [Visual testing](#visual-testing)
     * [Android](#android-6)
     * [iOS](#ios-3)
  * [Stress testing](#stress-testing)
     * [Android](#android-7)
     * [iOS](#ios-4)
  * [Linked](#linked)
  * [Books](#books)
  * [Security](#security)
     * [OWASP](#owasp)
     * [Android](#android-8)
     * [iOS](#ios-5)
  * [Static analysis](#static-analysis)
     * [Android](#android-9)
     * [iOS](#ios-6)
     * [Multiplatform](#multiplatform)
  * [App state restoring](#app-state-restoring)
     * [Android](#android-10)
        * [Fill RAM](#fill-ram)
  * [Web Services](#web-services)
     * [Analytics](#analytics)
     * [Cloud Testing](#cloud-testing)
     * [Device Farm](#device-farm)
     * [Crowd Testing](#crowd-testing)
* [TO DO:](#to-do)

## Mindmap
![Quality in mobile apps mindmap](images/quality_mobile_apps_mindmap.png)

To edit I use [Xmind](http://www.xmind.net/)

## Legend
:moneybag: - Paid services, tools, etc

## Accessibility

### Android
* [Accessibility - docs](https://developer.android.com/guide/topics/ui/accessibility/index.html)
* [Accessibility Developer Checklist](https://developer.android.com/guide/topics/ui/accessibility/checklist.html)

#### Tools
* [Accessibility Scanner](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor)

### iOS
* [Accessibility - docs](https://developer.apple.com/accessibility/ios/)
* [iOS Accessibility Tutorial: Getting Started](https://www.raywenderlich.com/142058/ios-accessibility-tutorial)

## Developer settings

### Android
* [Barstool](https://github.com/wmbest2/Barstool)
* [QualityMatters](https://github.com/artem-zinnatullin/qualitymatters)
* [Bee](https://github.com/orhanobut/bee)
* [U+2020](https://github.com/JakeWharton/u2020)
* [Under the Hood - Android App Debug View Library](https://github.com/patrickfav/under-the-hood)

## Debug

### Android
* [Stetho](http://facebook.github.io/stetho/)
* [PID Cat](https://github.com/JakeWharton/pidcat)

## Reverse engineering

### Android
* [Apktool](https://ibotpeaches.github.io/Apktool/)

## Screen mirroring

### Android
* [Mobizen](https://www.mobizen.com/)
* [Vysor](https://www.vysor.io/) :moneybag:

### iOS
* QuickTime

## Emulator/simulator

### Android
* [Android SDK](https://developer.android.com/studio/run/managing-avds.html)
    * [Intel HAXM](https://software.intel.com/en-us/android/articles/intel-hardware-accelerated-execution-manager)
* [Genymotion](https://www.genymotion.com/) :moneybag:

### iOS
* [Xcode simulator](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/iOS_Simulator_Guide/Introduction/Introduction.html)
* [simctl: Control iOS Simulators from Command Line](http://shashikantjagtap.net/simctl-control-ios-simulators-command-line/?utm_content=buffer5c6da)

## Manual testing
* Eploratory testing - sprints
* Checklists
* Bug Hunts
* [Mob testing](http://www.slideshare.net/maaretp/mob-testing)
* [Testing dojo](http://www.methodsandtools.com/archive/archive.php?id=114)

## Visual testing

### Android
* [screenshot-tests-for-android](http://facebook.github.io/screenshot-tests-for-android/)
* [Designer Tools](https://play.google.com/store/apps/details?id=com.scheffsblend.designertools)

### iOS
* [FBSnapshotTestCase](https://github.com/facebook/ios-snapshot-test-case)
* [Flawless App](https://flawlessapp.io/) :moneybag:

## Stress testing

### Android
* [UI/Application Exerciser Monkey](https://developer.android.com/studio/test/monkey.html)
* [Android Developer Toolbelt](https://github.com/T-Spoon/Android-Developer-Toolbelt)

### iOS
* [ui-auto-monkey](https://github.com/jonathanpenn/ui-auto-monkey) - DEPRECATED
* [Chaos Testing on iOS](https://github.com/jonathanpenn/ui-auto-monkey)
* [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey)
* [SwiftMonkey](https://github.com/zalando/SwiftMonkey)

## Linked
* [Visualizing and optimizing real user performance on mobile - LinkedIn](https://www.facebook.com/atscaleevents/videos/vl.531312673697503/1693979707541793/?type=1)
* [Android Performance Case Study: Memory vs. Frame Time](http://blog.karumi.com/android-performance-case-study-memory-vs-frame-time/)
* [10 Mobile App Testing Mistakes to Avoid](http://adventuresinqa.com/2016/05/03/10-mobile-app-testing-mistakes-to-avoid/)
* [Smartwatch Testing Cheat Sheet](http://adventuresinqa.com/2016/05/30/smartwatch-testing-cheat-sheet/)
* [Mobile Testing Cheat Sheet](http://adventuresinqa.com/2016/01/11/mobile-testing-cheat-sheet/)
* [The Mobile Test Pyramid](http://www.ministryoftesting.com/2014/10/mobile-test-pyramid/)
* [Introducing the Software Testing Cupcake (Anti-Pattern)](https://www.thoughtworks.com/insights/blog/introducing-software-testing-cupcake-anti-pattern)
* [Richard Bradshaw, keynote: "Mobile - the clue is in the name"](https://www.youtube.com/watch?v=CWMZXmkGPEI)
* [Understanding Your Mobile User](http://www.slideshare.net/sjanaway/understanding-your-mobile-user)
* [Android Development Culture. The Document. #qualitymatters](https://artemzin.com/blog/android-development-culture-the-document-qualitymatters/)
    * [QualityMatters](https://github.com/artem-zinnatullin/qualitymatters)
* [Android Performance monitoring [Part 1]](https://blog.mindorks.com/android-performance-monitoring-part-1-1ce1b8df8a12#.xvmd7s505)
* [Useful tips to inspect your Android app — Part 1](https://medium.com/freenet-engineering/useful-tips-to-inspect-your-android-app-part-1-34415239e91a#.t59kbicht)
* [The 2016 Android Developer Toolbox](https://realm.io/news/mobilization-gautier-mechling-the-2016-android-developer-toolbox/)
* [The complete Checklist for Mobile Testing | David Tzemach](http://www.machtested.com/2016/07/mobile-testing-checklist-david-tzemach.html)
* [Mobile Testing of Location-Powered Android Apps](http://blog.perfectomobile.com/mobile-application-testing/continuous-mobile-testing-of-location-powered-apps-with-perfecto/)

## Books
* [Hands-On Mobile App Testing By Daniel Knott](http://www.informit.com/store/hands-on-mobile-app-testing-a-guide-for-mobile-testers-9780134191713)

## Security
* [Mobile Security Wiki](https://mobilesecuritywiki.com/)

### OWASP
* [OWASP Mobile Security Project](https://www.owasp.org/index.php/OWASP_Mobile_Security_Project)
* [OWASP Mobile Security Testing Guide](https://www.owasp.org/index.php/OWASP_Mobile_Security_Testing_Guide)

### Android
* [android-security-awesome](https://github.com/ashishb/android-security-awesome)
* [Mobile Security Framework (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
* [Fridump](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
* [How to get started with mobile penetration testing for Android](https://learn.techbeacon.com/units/how-get-started-mobile-penetration-testing-android)

### iOS
* [Hacking iOS Applications](https://web.securityinnovation.com/hubfs/iOS%20Hacking%20Guide.pdf)
* [How to get started with mobile penetration testing for iOS](https://learn.techbeacon.com/units/how-get-started-mobile-penetration-testing-ios)

## Static analysis

### Android
* [SDK lint](https://developer.android.com/studio/write/lint.html)
    * [How To Create Your Own Lint Rule](http://blog.xebia.com/how-to-create-your-own-lint-rule/)
* [PMD](https://pmd.github.io/)
* [error-prone](https://github.com/google/error-prone)
* [FindBugs](http://findbugs.sourceforge.net/)
* [rxlint](https://bitbucket.org/littlerobots/rxlint)
* [checkstyle](http://checkstyle.sourceforge.net/)
* [klint](https://github.com/shyiko/ktlint)
* [SonarLint](http://www.sonarlint.org/intellij/)
* [detekt](https://github.com/arturbosch/detekt)

### iOS
* [SwiftLint](https://github.com/realm/SwiftLint)
* [Xcode Analyze](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/debugging_with_xcode/chapters/static_analyzer.html)

### Multiplatform
* [SonarQube](https://www.sonarqube.org/)

## App state restoring

### Android
* [Don’t Keep Activities](http://stackoverflow.com/a/22402360)

#### Fill RAM
* [Fill RAM memory](https://play.google.com/store/apps/details?id=me.empirical.android.application.fillmemory&hl=pl)
* [Android Toollbelt](https://play.google.com/store/apps/details?id=com.tspoon.androidtoolbelt&hl=pl)
    * [Android Developer Toolbelt](https://github.com/T-Spoon/Android-Developer-Toolbelt)
* [MemoryPump](https://play.google.com/store/apps/details?id=com.fabsimilian.memorypump&rdid=com.fabsimilian.memorypump)

## Web Services

### Analytics
* [Dynatrace](https://www.dynatrace.com/solutions/application-monitoring/) :moneybag:
* [monit24](https://monit24.pl/) :moneybag:
* [New Relic](https://newrelic.com/mobile-monitoring) :moneybag:
* [FlowUp](http://flowup.io/):moneybag:
* [Raygun](https://raygun.com/products/real-user-monitoring) :moneybag:
* [Bugsee](https://www.bugsee.com/) :moneybag:
* [Fabric](https://fabric.io)
* [Hockeyapp](https://www.hockeyapp.net/) :moneybag:
* [Splunk](https://mint.splunk.com/) :moneybag:
* [Appsee](https://www.appsee.com/) :moneybag:
* [Appachhi](https://appachhi.com/) :moneybag:

### Cloud Testing
* [Monkop](https://appachhi.com/) :moneybag:
* [NimbleDroid](https://nimbledroid.com) :moneybag:
* [Appdiff](https://www.appdiff.com/) :moneybag:

### Device Farm
* [Kobiton (free beta)](https://kobiton.com/)
* [Testdroid](http://bitbar.com/testing/) :moneybag:
* [TestObject](https://testobject.com/) :moneybag:
* [Perfecto Mobile](https://www.perfectomobile.com/) :moneybag:
* [Nativetap.io](https://nativetap.io/) :moneybag:
* [AWS Device Farm](https://aws.amazon.com/device-farm/) :moneybag:
* [Google Firebase](https://firebase.google.com/docs/test-lab/) :moneybag:
* [Xamarin Test Cloud](https://www.xamarin.com/test-cloud) :moneybag:
* [Experitest](https://experitest.com/) :moneybag:
* [Samsung Remote Test Lab](http://developer.samsung.com/rtlLanding.do)
* [pCloudy](https://www.pcloudy.com/) :moneybag:
* [robotic.mobi](https://robotic.mobi/) :moneybag:

### Crowd Testing
* [Ubertesters](https://ubertesters.com/)
* [TestFairy](https://testfairy.com/)
* [Beta Family](https://betafamily.com/)
* [Applause](https://www.applause.com)
* [Testarmy](http://testarmy.com/)
* [crowdsourcedtesting](https://crowdsourcedtesting.com/)
* [Comparing 11 Mobile Beta Testing Tools](https://dzone.com/articles/comparing-11-mobile-beta-testing-tools)

# TO DO:
Stats

CPU

Android

CPU Monitor

iOS

Measure CPU Use

RAM

Android

Memory Monitor

A useful memory debugger plugin for Android Studio

JVM Debugger Memory View
for IntelliJ IDEA

iOS

Monitor Memory Usage

Battery

Android

[Guide] Finding battery issues with Google's Battery Historian (no root)    

iOS

Optimising battery while building iOS apps

Debugging Energy Issues

Network Usage

Time between multiple independent events

Speed

Android

Takt

AndroidDevMetric

Pury

Tiny Dancer

FrameMetrics

Testing Android UI Performance

iOS

WatchdogInspector

FPSStatusBar

GodEye

Monitoring

Grafana

Duration of the method

Android

Hugo

Backend

API Chaos

Endpoint performance

Health status

Network

Proxy

Charles Proxy
Tags: Cry

Bandwidth Throttle

Rewrite Tool

Breakpoints Tool

Map Remote Tool

Map Local Tool

Trusting custom root certificates on ios 10.3

Burp

How to Monitor Mobile App Traffic With Sniffers

Fiddler

Tools

Augmented Traffic Control

Network Link Conditioner

Automated checking

Unit test

Android

Roboelectric

JUnit

RoboSpock

JacocoEverywhere

iOS

XCTest

Techniques

Test Driven Development (TDD)

Behaviour Driven Development (BDD)

 Acceptance Test Driven Development (ATDD)

e2e

iOS

XCTest

KIF

EarlGrey

iOS-driver

Android

Espresso

Cappuccino

Robotium

UI Automator

Selendroid

Magneto

Mobly

AndroidViewClient

monkey

Multiplatform

Calabash

Appium

Appium Studio

Helpers

Android

Test Butler

Spoon

Composer

Swarmer

iOS

Bluepill

Open Sourcing Bluepill: Run iOS Tests in Multiple Simulators

pxctest

Multiplatfom

App Inspector

AppiumTestDistribution

Pattern

Robot

Instrumentation Testing Robots

Other

Android

Mobile Testing of Location Powered Android Apps

Android

AndroidTestingBox

Android Testing Guide

Android Testing with Kotlin

Using Kotlin to test Android Applications

Running Android UI Tests

Test farm

Android

STF

Introducing “gnirehtet”, a reverse tethering tool for Android

Other

DeviceNanny

Leaks

Android

LeakCanary

BlockCanary

BlockCanaryEx

iOS

Finding iOS Memory Leaks with Xcode’s Instruments 

 - Paid services, tools, etc
Tags: Cry


