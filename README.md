# TaskPadi

## Description
 This is a basic architecture repository that contains the standard functionality for TaskPadi Web and Mobile app.

## Setting up the app for IOS

1. Run `flutter pub get` from the root of the project to fetch all dependencies
2. Run `flutter run` to start the app
3. cd ios
4. rm -rf Podfile.lock
5. rm -rf Pods
6. rm -rf pubspec.lock
7. pod repo update
8. pod cache clean --all
9. pod deintegrate
10. pod setup
11. pod install --repo-update


## Creating a Build for both Android and Web

1. flutter build apk --target-platform android-arm,android-arm64,android-x64 --split-per-abi

2. flutter run -d chrome --web-hostname localhost --web-port 5000


## Flutterwave Test Card

Visa Card 3DS authentication 2	4242424242424242	812	3310	01/31	12345

https://docs.google.com/document/d/1Py51u0vlNzTWXsUJGpe1Ghbw4kRyVmN1z3Ii5VpW7xc/edit

https://docs.google.com/document/d/1ESNtMD2Qwimtwv0pPbcpLEq72J8uN1uN0iVUdL9fQ7M/edit
