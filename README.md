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
  * [Stats](#stats)
     * [CPU](#cpu)
        * [Android](#android-11)
        * [iOS](#ios-7)
     * [RAM](#ram)
        * [Android](#android-12)
        * [iOS](#ios-8)
     * [Battery](#battery)
        * [Android](#android-13)
        * [iOS](#ios-9)
     * [Speed](#speed)
        * [Android](#android-14)
        * [iOS](#ios-10)
     * [Monitoring](#monitoring)
     * [Duration of the method](#duration-of-the-method)
        * [Android](#android-15)
     * [Other](#other)
        * [Network Usage](#network-usage)
        * [Time between multiple independent events](#time-between-multiple-independent-events)
  * [Backend](#backend)
     * [API Chaos](#api-chaos)
     * [Endpoint performance](#endpoint-performance)
     * [Health status](#health-status)
  * [Network](#network)
     * [Proxy](#proxy)
     * [Tools](#tools-1)
  * [Automated checking](#automated-checking)
     * [Unit test](#unit-test)
        * [Android](#android-16)
     * [iOS](#ios-11)
     * [Coverage](#coverage)
        * [Android](#android-17)
     * [Techniques](#techniques)
     * [e2e](#e2e)
        * [Android](#android-18)
        * [iOS](#ios-12)
     * [Multiplatform](#multiplatform-1)
     * [Helpers](#helpers)
        * [Android](#android-19)
        * [iOS](#ios-13)
           * [Multiplatfom](#multiplatfom)
     * [Pattern](#pattern)
        * [Robot](#robot)
     * [Other](#other-1)
        * [Android](#android-20)
  * [Android](#android-21)
  * [Test farm](#test-farm)
     * [Android](#android-22)
     * [Other](#other-2)
  * [Leaks](#leaks)
     * [Android](#android-23)
     * [iOS](#ios-14)

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
* [Automated Performance Testing Codelab](https://codelabs.developers.google.com/codelabs/android-perf-testing/index.html)

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
* [Dependency Injection usage Checks](https://github.com/groupon/dependency-injection-checks)

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
* [Ubertesters](https://ubertesters.com/) :moneybag:
* [TestFairy](https://testfairy.com/) :moneybag:
* [Beta Family](https://betafamily.com/) :moneybag:
* [Applause](https://www.applause.com) :moneybag:
* [Testarmy](http://testarmy.com/) :moneybag:
* [crowdsourcedtesting](https://crowdsourcedtesting.com/) :moneybag:
* [Comparing 11 Mobile Beta Testing Tools](https://dzone.com/articles/comparing-11-mobile-beta-testing-tools)

## Stats

### CPU

#### Android
* [CPU Monitor](https://developer.android.com/studio/profile/am-cpu.html)

#### iOS
* [Measure CPU Use](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MeasuringCPUUse.html)

### RAM

#### Android
* [Memory Monitor](https://developer.android.com/studio/profile/am-memory.html)
* [A useful memory debugger plugin for Android Studio](https://medium.com/@m_mirhoseini/a-useful-memory-debugger-plugin-for-android-studio-2d9d95bddc24#.mwvfhldy5)
    * [JVM Debugger Memory View for IntelliJ IDEA](https://plugins.jetbrains.com/idea/plugin/8537-jvm-debugger-memory-view)

#### iOS
* [Monitor Memory Usage](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MonitoringMemoryUsage.html)

### Battery

#### Android
* [[Guide] Finding battery issues with Google's Battery Historian (no root)](https://www.reddit.com/r/Android/comments/5bb606/guide_finding_battery_issues_with_googles_battery/)

#### iOS
* [Optimising battery while building iOS apps](https://medium.com/@nikhilmshchs/optimising-ios-battery-5f0f3beadae7#.ulsuwrn0z)
* [Debugging Energy Issues](https://developer.apple.com/videos/play/wwdc2015/708/)

### Speed

#### Android
* [Takt](https://github.com/wasabeef/Takt)
* [AndroidDevMetric](https://github.com/frogermcs/AndroidDevMetrics)
* [Pury](https://github.com/NikitaKozlov/Pury)
* [Tiny Dancer](https://github.com/friendlyrobotnyc/TinyDancer)
* [FrameMetrics](https://medium.com/@froger_mcs/framemetrics-realtime-app-smoothness-tracking-3d8550413c1c#.jzhowg88o)
* [Testing Android UI Performance](http://dtmilano.blogspot.com/2017/04/testing-android-ui-performance.html)

#### iOS
* [WatchdogInspector](https://github.com/tapwork/WatchdogInspector)
* [FPSStatusBar](https://github.com/asaday/FPSStatusBar)
* [GodEye](https://github.com/zixun/GodEye)

### Monitoring
* [Grafana](http://grafana.org/)

### Duration of the method

#### Android
* [Hugo](https://github.com/JakeWharton/hugo)

#### iOS
* [Continuous Performance Testing of an iOS Apps using XCTest](http://shashikantjagtap.net/continuous-performance-testing-ios-apps-using-xctest/)

### Other

#### Network Usage

#### Time between multiple independent events

## Backend

### API Chaos

### Endpoint performance

### Health status

## Network

### Proxy
* [Charles Proxy](https://www.charlesproxy.com/) :moneybag:
    * [Bandwidth Throttle](https://www.charlesproxy.com/documentation/proxying/throttling/)
    * [Rewrite Tool](https://www.charlesproxy.com/documentation/tools/rewrite/)
    * [Breakpoints Tool](https://www.charlesproxy.com/documentation/proxying/breakpoints/)
    * [Map Remote Tool](https://www.charlesproxy.com/documentation/tools/map-remote/)
    * [Map Local Tool](https://www.charlesproxy.com/documentation/tools/map-local/)
    * [Trusting custom root certificates on ios 10.3](http://www.neglectedpotential.com/2017/04/trusting-custom-root-certificates-on-ios-10-3/)
    * [How to get charles proxy work with Android 7 nougat?](https://stackoverflow.com/questions/39215229/how-to-get-charles-proxy-work-with-android-7-nougat)
        * [Add Securiy Exception to APK](https://github.com/levyitay/AddSecurityExceptionAndroid)
* [Burp](https://portswigger.net/burp/)
    * [How to Monitor Mobile App Traffic With Sniffers](https://stanfy.com/blog/monitor-mobile-app-traffic-with-sniffers/)
* [Fiddler](http://www.telerik.com/fiddler)

### Tools
* [Augmented Traffic Control](https://github.com/facebook/augmented-traffic-control)
* [Network Link Conditioner](http://nshipster.com/network-link-conditioner/)
* [Cellular Data Network Simulator](https://github.com/Polidea/Cellular-Data-Network-Simulator)

## Automated checking

### Unit test

#### Android
* [Roboelectric](http://robolectric.org/)
* [JUnit](https://developer.android.com/training/testing/unit-testing/local-unit-tests.html)
* [RoboSpock](http://robospock.github.io/RoboSpock/)

### iOS
* [XCTest](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/04-writing_tests.html)

### Coverage

#### Android
* [JacocoEverywhere](https://github.com/paveldudka/JacocoEverywhere)

### Techniques
* [Test Driven Development (TDD)](https://www.agilealliance.org/glossary/tdd/)
* [Behaviour Driven Development (BDD)](https://www.agilealliance.org/glossary/bdd/)
* [Acceptance Test Driven Development (ATDD)](https://www.agilealliance.org/glossary/atdd/)

### e2e

#### Android
* [Espresso](https://google.github.io/android-testing-support-library/docs/espresso/)
    * [Cappuccino](https://github.com/autonomousapps/Cappuccino)
    * [Barista](https://github.com/SchibstedSpain/Barista)
* [Robotium](https://github.com/RobotiumTech/robotium)
* [UI Automator](https://developer.android.com/topic/libraries/testing-support-library/index.html#UIAutomator)
* [Selendroid](http://selendroid.io/)
* [Magneto](http://getmagneto.com/)
* [Mobly](https://github.com/google/mobly)
* [AndroidViewClient](https://github.com/dtmilano/AndroidViewClient)
* [monkey](https://developer.android.com/studio/test/monkeyrunner/index.html)
* [DroidBot](https://github.com/honeynet/droidbot)

#### iOS
* [XCTest](https://developer.apple.com/library/ios/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/01-introduction.html)
* [KIF](https://github.com/kif-framework/KIF)
* [EarlGrey](https://github.com/google/EarlGrey)
* [iOS-driver](http://ios-driver.github.io/ios-driver/)

### Multiplatform
* [Calabash](http://calaba.sh/) - DEPRECATED
* [Appium](http://appium.io/)
    * [Appium Studio](https://experitest.com/appium-studio/)

### Helpers

#### Android
* [Test Butler](https://github.com/linkedin/test-butler)
* [Spoon](https://github.com/square/spoon)
* [Composer](https://github.com/gojuno/composer)
* [Swarmer](https://github.com/gojuno/swarmer)

#### iOS
* [Bluepill](https://github.com/linkedin/bluepill)
    * [Open Sourcing Bluepill: Run iOS Tests in Multiple Simulators](https://engineering.linkedin.com/blog/2017/01/open-sourcing-bluepill--run-ios-tests-in-multiple-simulators)
* [pxctest](https://github.com/plu/pxctest)

##### Multiplatfom
* [App Inspector](https://macacajs.github.io/app-inspector/)
* [AppiumTestDistribution](https://github.com/saikrishna321/AppiumTestDistribution)

### Pattern

#### Robot
* [Instrumentation Testing Robots](https://realm.io/news/kau-jake-wharton-testing-robots/)

### Other

#### Android
* [Mobile Testing of Location Powered Android Apps](http://blog.perfectomobile.com/mobile-application-testing/continuous-mobile-testing-of-location-powered-apps-with-perfecto/)

## Android
* [AndroidTestingBox](https://roroche.github.io/AndroidTestingBox)
* [Android Testing Guide](https://ravidsrk.github.io/android-testing-guide/)
* [Android Testing with Kotlin](https://fernandocejas.com/2017/02/03/android-testing-with-kotlin/)
* [Using Kotlin to test Android Applications](https://stories.nevercode.io/using-kotlin-to-test-android-applications-6a8549dc411a)
* [Running Android UI Tests](https://www.reddit.com/r/androiddev/comments/622a9u/running_android_ui_tests_collect_logs_record_a)

## Test farm

### Android
* [STF](https://openstf.io/)
* [Introducing “gnirehtet”, a reverse tethering tool for Android](https://medium.com/genymobile/gnirehtet-reverse-tethering-android-2afacdbdaec7)

### Other
* [DeviceNanny](https://github.com/hudl/DeviceNanny)

## Leaks

### Android
* [LeakCanary](https://github.com/square/leakcanary)
* [BlockCanary](https://github.com/markzhai/AndroidPerformanceMonitor)
    * [BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx)

### iOS
* [Finding iOS Memory Leaks with Xcode’s Instruments](https://spin.atomicobject.com/2016/01/25/ios-memory-leak-xcode)
