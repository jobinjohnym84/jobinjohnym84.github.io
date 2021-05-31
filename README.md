# Introduction

The intention of this repository is to create a Portfolio using Flutter. Single code repo for Web, Android and iOS.

# Tools used

a) VS Code  b) XCode  

# Technology Stack

  1. Flutter
  2. Dart
  3. HTML


# Dev Steps

1. Git clone
2. cd
3. flutter packages get
4. flutter config --enable-web
5. flutter run -d chrome


# Flutter Setup MAC

Follow this link - https://flutter.dev/docs/get-started/install/macos


# Deployment Steps - Web

1. flutter build web
2. Copy the build folder and host it.


# Deployment Steps - IOS

1. Install Latest Xcode and upgrade your iPhone OS to latest
2. sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
3. sudo xcodebuild -runFirstLaunch
4. sudo gem install cocoapods
5. Run this from VSCode Terminal - open ios/Runner.xcworkspace
6. Once VS code is opened - Select the Runner project in the left navigation panel.
7. In the Runner target settings page, make sure your Development Team is selected under Signing & Capabilities > Team.
8. Sign in to Apple ID
9. cd ios/
10. pod install
11. Go to the main directory and flutter run --release
12. Above will compile and will install to Physical device
