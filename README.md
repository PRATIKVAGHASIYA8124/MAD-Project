# A simplified Real Movie Booking App 🎬 🍿 - Built with Flutter, Clean Template, BLoC, REST API, Firebase Auth, and Unit-Tests.

## 🎬 Working application

Check out the **live web demo** -> _coming soon_ 

<table>
  <tr>
    <th>Screen</th>
    <th>Preview</th>
    <th>Screen</th>
    <th>Preview</th>
  </tr>
  <tr>
    <td><strong>Begin Screen</strong></td>
    <td><img src="media/images/begin_screen.png" width="300"></td>
    <td><strong>Get Start Screen</strong></td>
    <td><img src="media/images/get_start.jpg" width="300"></td>
  </tr>
  <tr>
    <td><strong>Home Screen</strong></td>
    <td><img src="media/images/home_screen.jpeg" width="300"></td>
    <td><strong>Movie Screen</strong></td>
    <td><img src="media/images/movie_screen.jpeg" width="300"></td>
  </tr>
  <tr>
    <td><strong>Login Screen</strong></td>
    <td><img src="media/images/login_screen.jpeg" width="300"></td>
    <td><strong>Register Screen</strong></td>
    <td><img src="media/images/register_screen.jpeg" width="300"></td>
  </tr>
  </tr>
    <tr>
    <td><strong>All Movie Screen</strong></td>
    <td><img src="media/images/all_movie_screen.jpeg" width="300"></td>
    <td><strong>About Screen</strong></td>
    <td><img src="media/images/about_screen.jpeg" width="300"></td>
  </tr>
  <tr>
    <td><strong>Booking Time</strong></td>
    <td><img src="media/images/booking_time.jpeg" width="300"></td>
    <td><strong>Booking Seat Type</strong></td>
    <td><img src="media/images/booking_seat_type.jpeg" width="300"></td>
  </tr>
  <tr>
    <td><strong>Booking Slot</strong></td>
    <td><img src="media/images/booking_slot.jpg" width="300"></td>
    <td><strong>Tickets Screen</strong></td>
    <td><img src="media/images/tickets_screen.jpg" width="300"></td>
  </tr>
</table>


## 🎬 Cinema Booking

### What Cinema Booking ?

Cinema Booking is an application that helps users search for and book movie tickets 🎟️ at cinemas in Hanoi. The app offers a user-friendly and cinematic interface, quick operations, and a convenient ticket-booking experience.

# 📦 Tech Stack

Some libraries are used in this project and shout out to them because they are very helpful for the community.

<table>
  <tr>
    <th>Category</th>
    <th>Library</th>
    <th>Description</th>
    <th>Logo</th>
  </tr>

  <!-- Framework -->
  <tr>
    <td>Framework</td>
    <td><a href="https://github.com/flutter/flutter">Flutter</a></td>
    <td>Flutter makes it easy and fast to build beautiful apps for mobile and beyond.</td>
    <td><img src="https://avatars.githubusercontent.com/u/14101776?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td>Language</td>
    <td><a href="https://github.com/dart-lang/sdk">Dart</a></td>
    <td>The Dart SDK, including the VM, JS and Wasm compilers, analysis, core libraries, and more.</td>
    <td><img src="https://avatars.githubusercontent.com/u/1609975?s=48&v=4" width="48"></td>
  </tr>

  <!-- Authentication -->

   <tr>
    <td>Authentication</td>
    <td><a href="https://github.com/firebase/flutterfire">Firebase Auth</a></td>
    <td>Handles user authentication.</td>
    <td><img src="https://firebase.google.com/downloads/brand-guidelines/SVG/logo-logomark.svg" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/flutter/packages/tree/main/packages/google_sign_in/google_sign_in">Google Sign-In</a></td>
    <td>Enables login via Google accounts.</td>
    <td><img src="https://avatars.githubusercontent.com/u/1342004?s=48&v=4" width="48"></td>
  </tr>

  <!-- State Management -->
  <tr>
    <td>State Management</td>
    <td><a href="https://github.com/felangel/bloc">Flutter BLoC</a></td>
    <td>A predictable state management library that helps implement the BLoC design pattern.</td>
    <td><img src="https://pub.dev/packages/flutter_bloc/versions/9.0.0/gen-res/gen/logo.webp" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/felangel/bloc/tree/master/packages/hydrated_bloc">Hydrated BLoC</a></td>
    <td>hydrated_bloc exports a Storage interface which means it can work with any storage provider. Out of the box, it comes with its own implementation: HydratedStorage.</td>
    <td><img src="https://pub.dev/packages/hydrated_bloc/versions/10.0.0/gen-res/gen/190x190/logo.webp" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/felangel/equatable">Equatable</a></td>
    <td>A Dart package that helps to implement value based equality without needing to explicitly override == and hashCode.</td>
    <td><img src="https://pub.dev/packages/equatable/versions/2.0.7/gen-res/gen/190x190/equatable_logo.webp" width="48"></td>
  </tr>
  </tr>
    <tr>
    <td>Support State Management</td>
    <td><a href="https://github.com/spebbe/dartz">dartz</a></td>
    <td>Dartz is a functional programming (FP) library for Dart, providing immutable data structures, type classes, monads, and tools inspired by Haskell.</td>
    <td><img src="https://avatars.githubusercontent.com/u/107203?v=4" width="48"></td>
  </tr>

  <!-- Dependency Injection -->
  <tr>
    <td>Dependency Injection</td>
    <td><a href="https://github.com/fluttercommunity/get_it">Get It</a></td>
    <td>Get It - Simple direct Service Locator that allows to decouple the interface from a concrete implementation and to access the concrete implementation from everywhere in your App.</td>
    <td><img src="https://avatars.githubusercontent.com/u/35045612?s=48&v=4" width="48"></td>
  </tr>

  <!-- Database & Storage -->
  <tr>
    <td>Database & Storage</td>
    <td><a href="https://github.com/firebase/flutterfire">Cloud Firestore</a></td>
    <td>Provides a NoSQL real-time database.</td>
    <td><img src="https://firebase.google.com/downloads/brand-guidelines/SVG/logo-logomark.svg" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/flutter/packages/tree/main/packages/shared_preferences/shared_preferences">Shared Preferences</a></td>
    <td>Wraps platform-specific persistent storage for simple data (NSUserDefaults on iOS and macOS, SharedPreferences on Android, etc.). Data may be persisted to disk asynchronously, and there is no guarantee that writes will be persisted to disk after returning, so this plugin must not be used for storing critical data.</td>
    <td><img src="https://avatars.githubusercontent.com/u/14101776?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/tekartik/sqflite">Sqflite</a></td>
    <td>Local SQLite database for persistent data.</td>
    <td><img src="https://avatars.githubusercontent.com/u/2605412?s=48&v=4" width="48"></td>
  </tr>

  <!-- Networking & API -->
  <tr>
    <td>Networking & API</td>
    <td><a href="https://github.com/cfug/dio">Dio</a></td>
    <td>A powerful HTTP client for Dart and Flutter, which supports global settings, Interceptors, FormData, aborting and canceling a request, files uploading and downloading, requests timeout, custom adapters, etc.</td>
    <td><img src="https://avatars.githubusercontent.com/u/44133785?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/trevorwang/retrofit.dart">Retrofit</a></td>
    <td>retrofit.dart is an dio client generator using source_gen and inspired by Chopper and Retrofit.</td>
    <td><img src="https://avatars.githubusercontent.com/u/121966?v=4" width="48"></td>
  </tr>

  <!-- UI & Effects -->
  <tr>
    <td>UI & Effects</td>
    <td><a href="https://github.com/flutter/packages/tree/main/third_party/packages/flutter_svg">Flutter SVG</a></td>
    <td>Draw SVG files and Render SVG images in Flutter.</td>
    <td><img src="https://avatars.githubusercontent.com/u/14101776?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/hnvn/flutter_shimmer">Shimmer</a></td>
    <td>A package provides an easy way to add shimmer effect in Flutter project by Vietnamese Developer.</td>
    <td><img src="https://avatars.githubusercontent.com/u/5468513?v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/serenader2014/flutter_carousel_slider">Carousel Slider</a></td>
    <td>A flutter carousel widget, support infinite scroll, and custom child widget..</td>
    <td><img src="https://avatars.githubusercontent.com/u/6716522?v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/ajilo297/Flutter-Dotted-Border">Dotted Border</a></td>
    <td>A Flutter package to easily add dashed borders around widgets.</td>
    <td><img src="https://avatars.githubusercontent.com/u/19208124?v=4" width="48"></td>
  </tr>

  <!-- Code Generation -->
  <tr>
    <td>Code Generation</td>
    <td><a href="https://github.com/google/json_serializable.dart">Json Serializable</a></td>
    <td>Generates utilities to aid in serializing to/from JSON.</td>
    <td><img src="https://avatars.githubusercontent.com/u/1342004?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td></td>
    <td><a href="https://github.com/rrousselGit/freezed">Freezed</a></td>
    <td>Code generation for immutable classes that has a simple syntax/API without compromising on the features.</td>
    <td><img src="https://avatars.githubusercontent.com/u/20165741?v=4" width="48"></td>
  </tr>
  </tr>
    <tr>
    <td></td>
    <td><a href="https://github.com/trevorwang/retrofit.dart/">retrofit_generator</a></td>
    <td>retrofit.dart is an dio client generator using source_gen and inspired by Chopper and Retrofit.</td>
    <td><img src="https://avatars.githubusercontent.com/u/121966?v=4" width="48"></td>
  </tr>
  </tr>
    <tr>
    <td>Navigation</td>
    <td><a href="https://github.com/flutter/packages/tree/main/packages/go_router">Go Router</a></td>
    <td>A declarative routing package for Flutter that uses the Router API to provide a convenient, url-based API for navigating between different screens. You can define URL patterns, navigate using a URL, handle deep links, and a number of other navigation-related scenarios.</td>
    <td><img src="https://avatars.githubusercontent.com/u/14101776?s=48&v=4" width="48"></td>
  </tr>

  <tr>
    <td>Video & Multimedia</td>
    <td><a href="https://github.com/sarbagyastha/youtube_player_flutter">YouTube Player Flutter</a></td>
    <td>A Flutter plugin for inline playback or streaming of YouTube videos using the official iFrame Player API.</td>
    <td><img src="https://raw.githubusercontent.com/sarbagyastha/youtube_player_flutter/main/packages/youtube_player_iframe/screenshots/logo.png" width="48"></td>
  </tr>

  <tr>
    <td>Google Maps</td>
    <td><a href="https://github.com/flutter/packages/tree/main/packages/google_maps_flutter/google_maps_flutter">Google Maps Flutter</a></td>
    <td>A Flutter plugin that provides a Google Maps widget. Displays Cinema locations on maps.</td>
    <td><img src="https://avatars.githubusercontent.com/u/14101776?s=48&v=4" width="48"></td>
  </tr>

  <!-- App Icons -->
  <tr>
    <td>App Icons</td>
    <td><a href="https://github.com/fluttercommunity/flutter_launcher_icons">Flutter Launcher Icons</a></td>
    <td>A package which simplifies the task of updating your Flutter app's launcher icon. Fully flexible, allowing you to choose what platform you wish to update the launcher icon for and if you want, the option to keep your old launcher icon in case you want to revert back sometime in the future.</td>
    <td><img src="https://avatars.githubusercontent.com/u/35045612?s=48&v=4" width="48"></td>
  </tr>
</table>
