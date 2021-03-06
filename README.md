# Android Developer Roadmap

> This fork: Less bullshit, more advanced and useful topics


## Roadmap to learn Android App Development
* Programming
   * Java
      * Syntax
      * Stdlib basics: collections, utilities
      * OOP concept, principles and patterns
      * Streams, FP concept
      * Multithreading
         * Thread and Runnable
         * Executor(s), ExecutorService, ThreadPoolExecutor
         * Future, CompletableFuture
   * Kotlin
      * Syntax, Generics, idioms
      * (Mutable)Collections, Sequences, inline functions, inline classes
      * Coroutines, Structured Concurrency
* Android Studio / IntelliJ IDEA
   * Android Studio IDE Overview
   * Project Structure
      * Java/Kotlin
      * XML
      * .gradle files
* Android Component
   * Activity
     * Activity Lifecycle
     * Tasks & Back Stack
     * nonConfigurationInstance, savedInstanceState
   * Service
     * IntentService
     * JobIntentService
   * Broadcast Receiver
   * Content Provider
* Intents
   * Types of Intent
     * Implicit
     * Explicit
   * Intent Filter
* Static User Interface
  * View
      * TextView, Button, EditText, ImageView, ImageButton, etc
  * ViewGroup
      * FrameLayout, LinearLayout, RelativeLayout, etc
* Dynamic User Interface
   * ListView, RecyclerView
   * ViewPager
   * Spinner
* User Interaction
   * ProgressBar
   * Dialogs
   * Toast & Snackbar
* UI Resources
   * Colour formats
   * Drawables (color, shape, selector, vector, ripple, bitmap, 9-patch)
   * String, Text (Spannable, CharSequence)
* Custom Views and Drawables
   * Canvas
   * Paint, TextPaint
   * Path
   * PorterDuff, Xfermode, ColorFilter
* Fragments
   * Fragment Lifecycle
   * Fragment Manager
   * Child fragments
* Storage
   * Raw files
   * Shared Preferences
   * SQLite database
* Build
  * Gradle
  * Debug / Release Configuration
* Threading
  * Handler and Looper, IdleHandler
  * HandlerThread
  * AsyncTask
  * IntentService
* Debugging and profiling
  * Debugger
  * Memory: heap dumps, memory leaks, LeakCanary
  * Sampling and Tracing, CPU profiler, Systrace, Nanoscope
  * Logging
  * Exceptions
  * Error Handling
* 3rd Party Libraries
  * Image Loading
     * Glide
     * Picasso
  * Networking
     * OkHttp
     * Retrofit
* Data Format
  * JSON
     * streaming: android.util.JsonReader/Writer
     * AST: org.json
     * mapping/binding: GSON, Moshi, Jackson or whatever
  * Unpopular but interesting: CBOR, Protobuf, FlatBuffers, Cap'n'Proto, and more
* Android Jetpack
  * Basic Components
     * AppCompat Activities and Fragments
     * Android KTX
     * Multidex
  * Behaviour Components 
     * Download Manager
     * Media Playback
     * Notification
     * Permissions
     * Preference
     * Sharing
     * Slice
  * UI Component
     * Animation & Transition
     * Emoji
     * Palette
* Architecture 
     * MVWhatever
* Unit Testing
    * Unit Testing
    * Robolectric
    * Instrumentation Testing
* Firebase
     * FCM
     * Crashlytics
     * Analytics
     * Remote Config
     * App Indexing
     * Dynamic Link
* Security
     * Keystore
     * SQLCipher
* Shrinking and obfuscation
     * AAPT shrinkResources
     * minifyEnabled, Proguard, R8
* App Release
     * .keystore file
     * App Bundle, Dynamic Feature
     * Playstore
* Keep Learning and Improving
