# AndroidPrep

Topics:


- [ ]  SOLID Principles with examples
- [ ]  KISS & DRY principles
- [ ]  Agile methodology
- [ ]  Kotlin vs Java
    - [ ]  conversion of kotlin code into java
        - [ ]  how extention functions get converted in java
    - [ ]  Object & it’s methods
- [ ]  Architecture patterns (MVVM, MVP, MVC, clean)
    - [ ]  Why MVVM is better?
- [ ]  Design patterns (Singleton, Factory, Obeserver, Builder, Adapter, Facade etc)
- [ ]  OOPs (https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)
    - [ ]  Access Modifiers in java
    - [ ]  Access Modifiers in Kotlin
- [ ]  Data Structure
    - [ ]  In java
    - [ ]  In Kotlin
    - [ ]  JNI (Java native interface)
    - [ ]  Primitive types in kotlin
    - [ ]  Primitive types in java
    - [ ]  internal working of Map, HashMap
    - [ ]  internal working of List
    - [ ]  List vs array
    - [ ]  mutable vs immutable
- [ ]  Multithreading
- [ ]  Activity lifecycle
    - [ ]  Performance enhancement to not destroy 1st activity from android 12
    - [ ]  Scenario based lifecycle (https://github.com/anandwana001/android-interview?tab=readme-ov-file#lifecycle)
- [ ]  Fragment lifecycle
    - [ ]  Scenario based lifecycle (https://github.com/anandwana001/android-interview?tab=readme-ov-file#lifecycle)
- [ ]  Android version changes
- [ ]  Tasks, backstack & launch modes
    - [ ]  Standard
    - [ ]  SingleTop
    - [ ]  SingleTask
    - [ ]  SingleInstance
- [ ]  viewmodel
    - [ ]  Viewmodel Providers
    - [ ]  configuration changes
    - [ ]  viewmodel internal working
    - [ ]  ViewModelFactory
    - [ ]  where does viewmodel stores data during orientation changes
- [ ]  How to Support ALL Screen Sizes on Android? (https://www.youtube.com/watch?v=5lSQcJjZPFs)
- [ ]  How to reduce size of App?
    - [ ]  Benifits?
    - Shrink, Optimize and Secure Your App With R8 & ProGuard (https://www.youtube.com/watch?v=bgpyuuzMlo0)
- [ ]  Why Do We Test Our Code? (https://www.youtube.com/watch?v=EkfVL5vCDmo&t=112s)
- [ ]  Context
    - Activity Context
    - Application context
- [ ]  Parcelable vs serializable
- [ ]  Apk vs App bundle
- [ ]  Intent
    - [ ]  Intent & intent filters
    - [ ]  Sticky intent
    - [ ]  Implicit intent
    - [ ]  explicit intent
- [ ]  XML (https://www.youtube.com/playlist?list=PLQkwcJG4YTCTq1raTb5iMuxnEB06J1VHX)
    - [ ]  Layout basics & Linear Layout
    - [ ]  Constraint layout
    - [ ]  Constraint layout vs relative layout
    - [ ]  Chains & guildelines (https://www.youtube.com/watch?v=PqkWT92BT3U)
    - [ ]  barriers vs guidelines
- [ ]  Basics
    - [ ]  Intent & starting activities
    - [ ]  passing data between activities
    - [ ]  passing data between fragments
        - [ ]  Using viewmodel
    - [ ]  SharedPreferces
        - apply vs commit
- [ ]  Notifications (https://www.youtube.com/watch?v=urn355_ymNA)
- [ ]  Services
    - Foreground
    - background
    - bound
    - services vs workManager
- [ ]  Broadcast receivers
    - [ ]  dynamic & static
- [ ]  Local broadcast receiver
- [ ]  Content providers
- [ ]  WorkManager
- [ ]  JobScheduler
- [ ]  Modules in android
- [ ]  Uris (Unique resource identifier)
- [ ]  Security for Android
    - Encryption & decryption
    - How to Hide & Protect API Keys in Your Android App (Reverse Engineering) (https://www.youtube.com/watch?v=-2ckvIzs0nU)
- [ ]  Permissions (https://www.youtube.com/watch?v=S4jkcRhembY)
- [ ]  Delegation in Kotlin (https://www.youtube.com/watch?v=MfJB-JhRAoQ)
- [ ]  Coroutines (https://www.youtube.com/playlist?list=PLQkwcJG4YTCQcFEPuYGuv54nYai_lwil_)
    - [ ]  Coroutines vs thread
    - [ ]  Dispatchers
        - [ ]  Main vs Main.Immediate
        - [ ]  Unconfined
    - [ ]  Coroutine Context
    - [ ]  Coroutine Builders
        - [ ]  runBlocking
        - [ ]  launch
        - [ ]  withContext
        - [ ]  Async and Await
    - [ ]  SupervisorScope
    - [ ]  Jobs, Waiting, Cancelation
    - [ ]  lifecycleScope vs viewModelScope vs GlobalScope
    - [ ]  which scope to use when?
    - [ ]  Coroutine ExcepltionHandlers & cancelation (https://www.youtube.com/watch?v=VWlwkqmTLHc&list=PLQkwcJG4YTCQcFEPuYGuv54nYai_lwil_&index=11)
    - [ ]  Suspend function
- [ ]  Kotlin basics (https://github.com/amitshekhariitbhu/android-interview-questions#kotlin)
    - [ ]  Sealed Class
    - [ ]  Constructors
    - [ ]  Data class
    - [ ]  Data class vs normal java model class
    - [ ]  inline class
    - [ ]  inner class
    - [ ]  Sealed Interfaces
    - [ ]  when vs switch
    - [ ]  init block
    - [ ]  lateinit vs lazy
    - [ ]  Null handling
    - [ ]  Covariance in Kotlin
    - [ ]  const vs val
    - [ ]  Object, Companion object
    - [ ]  Annotation in Kotlin
        - JvmStatic
        - JvmField
        - JvmOverloads
- [ ]  Kotlin function
    - [ ]  inFix function
    - [ ]  extention function
    - [ ]  inline function
    - [ ]  noinline function
    - [ ]  crossinline function
    - [ ]  higher order functions
    - [ ]  invoke function
- [ ]  Kotlin Scope functions (https://www.youtube.com/watch?v=Vy-dS2SVoHk)
    - [ ]  Let
    - [ ]  Also
    - [ ]  Apply
    - [ ]  Run
    - [ ]  With
    - Summary of Scope functions:
    let: Used to check nulls, also better than simple null check in multi-threading case
    also: same as 'let'  but it doesn't return the last line as 'let', instead 'also'  will return the object it was called on and 'not the last line!'
    apply: helpful function to modify objects, if you want to change in properties of the objects, and it uses 'this' instead of 'it' as we work inside the class of the object
    run: equivalent to 'apply', but it won't return the object it was called, instead it will return the last line
    with: same as 'run' but a different signature.
- [ ]  Kotlin Flows (https://github.com/amitshekhariitbhu/android-interview-questions?tab=readme-ov-file#kotlin-flow-api)
    - StateFlow
    - Flow
    - SharedFlow
    - StateFlow vs. Flow vs. SharedFlow vs. LiveData (https://www.youtube.com/watch?v=6Jc6-INantQ)
- [ ]  Gradle (Build Types, Product Flavors, Build Variants, Source Sets) (https://www.youtube.com/watch?v=o0M4f5djJTQ)
- [ ]  OutOfMemoryExeption
- [ ]  Memory leaks
- [ ]  CompileSdkVersion vs TargetedSdkVersion
- [ ]  ANR (application not responding)
- [ ]  ViewBinding
- [ ]  DataBinding
    - [ ]  two-way binding
- [ ]  Retrofit (https://www.youtube.com/watch?v=t6Sql3WMAnk)
    - Interceptors
    - Authenticator
    - how to refresh token
    - error handling
    - annotations
    - sending data, headers
- [ ]  Room (https://www.youtube.com/watch?v=bOd3wO0uFr8)
- [ ]  Dependency Injection
- [ ]  Jetpack Compose
    - [ ]  Compose
    - [ ]  State: remember, rememberSaveable, MutableState
    - [ ]  Recomposition
    - [ ]  State hoisting
    - [ ]  Side-effects
    - [ ]  launch effect
    - [ ]  disposableEffect
    - [ ]  composable function vs normal function
    - [ ]  stateless vs stateful
    - [ ]  Modifier
    - [ ]  Theme
    - [ ]  Layout, List
    - [ ]  Gestures, Animation
    - [ ]  CompositionLocal
- [ ]  Unit testing
    - [ ]  Mock vs sub
    - [ ]  Annotations
    - [ ]  UI testing
    - [ ]  Dependencies
- [ ]  RxJava
- [ ]  StringBuilder
- [ ]  Firebase
- [ ]  ExoPlayer
    - [ ]  deprecation?
- [ ]  WebSockets
    - [ ]  heat-up the device?
- [ ]  Battery (Doze mode, low battery)
- [ ]  Storage
    - Internal
    - External
    - Cache (LRU)
    - ways to store in android
- [ ]  Android TV
    - [ ]  display different sizes
    - [ ]  Orientation
    - [ ]  Memory management
    - [ ]  Auto start on boot
    - [ ]  Elo Device
    - [ ]  Fire stick
    - [ ]  M2 device
    - [ ]  Kiosk mode
    - [ ]  Leankback
    - [ ]  view focus
    - [ ]  Remote navigation
