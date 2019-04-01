### Core Android

#### Base

* Tell all the Android application components. [Android Official](https://developer.android.com/guide/components/fundamentals.html#Components)

* What is the structure of an Android Application?

* What is `Context`? How is it used? [MindOrks](https://blog.mindorks.com/understanding-context-in-android-application-330913e32514)

* What is `AndroidManifest.xml`? [Android Official](https://developer.android.com/guide/topics/manifest/manifest-intro)

* What is `Application` class?

#### Activity

* What is `Activity`? [MindOrks](https://blog.mindorks.com/android-activity-lifecycle)

* Explain `Activity` and `Fragment` lifecycle. (Complete diagram [GitHub](https://github.com/xxv/android-lifecycle), simplified diagram for [Activity](https://developer.android.com/guide/components/activities/activity-lifecycle.html#alc), [Fragment](https://developer.android.com/guide/components/fragments.html#Lifecycle)), [Activity lifecycle](https://blog.mindorks.com/android-activity-lifecycle) and [Fragments lifecycle](https://blog.mindorks.com/android-fragments-and-its-lifecycle)

* What are "launch modes"? [MindOrks](https://blog.mindorks.com/android-activity-launchmode-explained-cbc6cf996802)

#### Fragments

* What is `Fragment`? [MindOrks](https://blog.mindorks.com/android-fragments-and-its-lifecycle)

* What is the difference between a `Fragment` and an `Activity`? Explain the relationship between the two.

* Why is it recommended to use only the default constructor to create a `Fragment`? [StackOverflow](https://stackoverflow.com/a/16042750/2809326)

* How would you communicate between two Fragments? [Android Official](https://developer.android.com/training/basics/fragments/communicating.html)

* What is retained `Fragment`? [AndroidDesignPatterns](https://www.androiddesignpatterns.com/2013/04/retaining-objects-across-config-changes.html)

#### Views and ViewGroups

* What is `View` in Android? [MindOrks](https://blog.mindorks.com/android-user-interface-view-components)

* Difference between `View.GONE` and `View.INVISIBLE`? [StackOverflow](https://stackoverflow.com/questions/11556607/android-difference-between-invisible-and-gone)

* Can you create custom views? How? Yes!Excellent documentation in [Google Developers Training advance course](https://google-developer-training.github.io/android-developer-advanced-course-concepts/unit-5-advanced-graphics-and-views/lesson-10-custom-views/10-1-c-custom-views/10-1-c-custom-views.html), custom views chapter

* What are ViewGroups and how they are different from the Views?

* What is a canvas?

* What is a `SurfaceView`?

* Relative Layout vs Linear Layout. [MindOrks](https://blog.mindorks.com/android-layout-relative-linear-frame)

* Tell about Constraint Layout [MindOrks](https://blog.mindorks.com/using-constraint-layout-in-android-531e68019cd)

* Do you know what is the view tree? How can you optimize its depth?

#### Displaying Lists of Content

* What is the difference between `ListView` and `RecyclerView`?

* What is the ViewHolder pattern? Why should we use it?

* What is `SnapHelper`? [MindOrks](https://blog.mindorks.com/using-snaphelper-in-recyclerview-fc616b6833e8)

#### Dialogs and Toasts

* What is `Dialog` in Android?

* What is `Toast` in Android?

* What the difference between `Dialog` and `Dialog Fragment`?

#### Intents and Broadcasting

* What is `Intent`? [StackOverflow](https://stackoverflow.com/questions/6578051/what-is-an-intent-in-android)

* What is an Implicit `Intent`?

* What is an Explicit `Intent`?

* What is a `BroadcastReceiver`? [StackOverflow](https://stackoverflow.com/questions/5296987/what-is-broadcastreceiver-and-when-we-use-it)

* What is a `LocalBroadcastManager`? [Developer Android](https://developer.android.com/reference/android/support/v4/content/LocalBroadcastManager.html)

* What is the function of an `IntentFilter`?

* What is a Sticky `Intent`? [AndroidInterview](http://www.androidinterview.com/what-is-a-sticky-intent/)

* Describe how broadcasts and intents work to be able to pass messages around your app?

* What is a `PendingIntent`?

* What are the different types of Broadcasts?

#### Services

* What is `Serivce`?

* `Service` vs `IntentService`. [StackOverflow](https://stackoverflow.com/a/15772151/5153275)

* What is a `JobScheduler`? [Vogella](http://www.vogella.com/tutorials/AndroidTaskScheduling/article.html)

#### Inter-process Communication

* How can two distinct Android apps interact?

* Is it possible to run an Android app in multiple processes? How?

* What is AIDL? Enumerate the steps in creating a bounded service through AIDL.

* What can you use for background processing in Android?

* What is a `ContentProvider` and what is it typically used for?

#### Long-running Operations

* How would you perform a long-running operation in an application?

* Why should you avoid to run non-ui code on the main thread?

* What is ANR? How can the ANR be prevented?

* What is an `AsyncTask`?

* What are the problems in asynctask?

* When would you use java thread instead of an asynctask?

* What is a `Loader`?

* What is the relationship between the life cycle of an `AsyncTask` and an `Activity`? What problems can this result in? How can these problems be avoided?

* Explain `Looper`, `Handler` and `HandlerThread`. [MindOrks](https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a) and [MindOrks Video](https://www.youtube.com/watch?v=rfLMwbOKLRk&list=PL6nth5sRD25hVezlyqlBO9dafKMc5fAU2)

#### Working With Multimedia Content

* How do you handle bitmaps in Android as it takes too much memory?

* What is the difference between a regular `Bitmap` and a nine-patch image?

* Tell about the `Bitmap` pool. [MindOrks](https://blog.mindorks.com/how-to-use-bitmap-pool-in-android-56c71a55533c)

* How to play sounds in Android? [Vogella](http://www.vogella.com/tutorials/AndroidMedia/article.html)

#### Data Saving

* How to persist data in an Android app? [MindOrks](https://blog.mindorks.com/android-shared-preferences-in-kotlin)

* What is ORM? How does it work?

* How would you preserve `Activity` state during a screen rotation? [StackOverflow](https://stackoverflow.com/questions/3915952/how-to-save-state-during-orientation-change-in-android-if-the-state-is-made-of-m)

* What are different ways to store data in your Android app?

#### Look and Feel

* What is a `Spannable`?

#### Memory Optimizations

* What is the `onTrimMemory()` method?

* How does the OutOfMemory happens?

* How do you find memory leaks in Android applications? [MindOrks](https://mindorks.com/blog/detecting-and-fixing-memory-leaks-in-android)

#### Battery Life Optimizations

* How to reduce battery usage in an android application? [MindOrks](https://blog.mindorks.com/battery-optimization-for-android-apps-f4ef6170ff70)

* What is Doze? What about App Standby?

* What is `overdraw`? [Developer Android](https://developer.android.com/topic/performance/rendering/overdraw.html)

#### Supporting Different Screen Sizes

* How did you support different types of resolutions?

#### Permissions

* What are the different protection levels in permission?

#### Native Programming

* What is the NDK and why is it useful?

* What is renderscript? [MindOrks](https://blog.mindorks.com/comparing-android-ndk-and-renderscript-1a718c01f6fe)

#### Android System Internal

* What is the Dalvik Virtual Machine?

* What is the difference JVM, DVM and ART?

* What are the differences between Dalvik and ART?

* What is DEX?

* Can you manually call the Garbage collector?

#### Debugging and Programming Tools

* What is ADB?

* What is DDMS and what can you do with it?

* What is the StrictMode? [MindOrks](https://blog.mindorks.com/use-strictmode-to-find-things-you-did-by-accident-in-android-development-4cf0e7c8d997)

* What is Lint? What is it used for?

#### Others

* Why Bundle class is used for data passing and why cannot we use simple Map data structure

* How do you troubleshoot a crashing application?

* Explain Android notification system?

* What is the difference between Serializable and Parcelable? Which is the best approach in Android?

* Have you developed widgets? Describe. [MindOrks](https://blog.mindorks.com/android-widgets-ad3d166458d3)

* What is AAPT?

* What is the best way to update the screen periodically?

* FlatBuffers vs JSON. [MindOrks](https://blog.mindorks.com/why-consider-flatbuffer-over-json-2e4aa8d4ed07)

* `HashMap`, `ArrayMap` and `SparseArray` [MindOrks](https://blog.mindorks.com/android-app-optimization-using-arraymap-and-sparsearray-f2b4e2e3dc47)

* What are Annotations? [Mindorks](https://blog.mindorks.com/creating-custom-annotations-in-android-a855c5b43ed9), [Link](https://blog.mindorks.com/improve-your-android-coding-through-annotations-26b3273c137a)

* How to handle multi-touch in android [GitHub](https://arjun-sna.github.io/android/2016/07/20/multi-touch-android/)

* How to implement XML namespaces?

* What is the support library? Why was it introduced?[MartianCraft](http://martiancraft.com/blog/2015/06/android-support-library/)

* What is Android Data Binding? [Developer Android](https://developer.android.com/topic/libraries/data-binding/index.html)

* What are Android Architecture Components? [MindOrks](https://blog.mindorks.com/what-are-android-architecture-components)

* How to implement search using RxJava operators? [MindOrks](https://blog.mindorks.com/implement-search-using-rxjava-operators-c8882b64fe1d)
