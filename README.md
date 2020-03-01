# Android Developer Roadmap

> This fork: Less bullshit, more advanced and useful topics


## Roadmap to learn Android App Development
* Programming
   * Java
      * Syntax
      * Collections and Streams
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
   * Drawables, Bitmaps, 9-patch
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
  * Memory profiling
  * Sampling and Tracing, CPU profiler, Systrace, Nanoscope
  * Logging
  * Exceptions
  * Error Handling
* Memory Leak
  * Detecting and Fixing Memory Leaks
  * Context
* 3rd Party Library
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
     * mapping: GSON, Moshi, Jackson or whatever
  * Unpopular but interesting: CBOR, Protobuf, FlatBuffers, Cap'n'proto, and more
* Android Jetpack
  * Foundation Components
     * AppCompat
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
     * Android Auto
     * Emoji
     * Palette
     * Android TV
     * Android Wear
* Architecture 
     * MVVWhatever
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
     * Proguard, R8
* App Release
     * .keystore file
     * App Bundle
     * Playstore
* Keep Learning and Improving


### License
```
   Copyright (C) 2019 MINDORKS NEXTGEN PRIVATE LIMITED

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

