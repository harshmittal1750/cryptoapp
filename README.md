
# Flutter cryptoapp
Complete Flutter Application



<img src="screenshots/1.jpeg" > 

## Features 
- Dark Theme


### Stack
- Flutter 2.2.0 (Null Safety)


### Testing
- Unit Testing (flutter_test)
- Integration Testing (integration_test)

- Github Actions (iOS & Android Integration Test)


## Setup project

Download project
```bash
git clone https://github.com/harshmittal1750/cryptoapp
```

Get flutter dependencies
```bash
flutter pub get
```



Run the app
```bash
flutter run
```

If you have any error with generated files try to run this
```bash
flutter pub run build_runner build --delete-conflicting-outputs
```


### Testing

Unit Test
```bash
flutter test
```
Integration Test
```bash
flutter drive --driver=test_driver/integration_test.dart --target=integration_test/main_test.dart
```

## Resources
[Flutter Docs](https://flutter.dev/docs)

[Riverpod Docs](https://riverpod.dev/docs/getting_started/)

[Cryptowatch Docs](https://docs.cryptowat.ch/rest-api/)


