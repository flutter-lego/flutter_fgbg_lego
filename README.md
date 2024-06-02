[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/flutter_fgbg_lego.svg)](https://pub.dartlang.org/packages/flutter_fgbg_lego)

# flutter_fgbg_lego
lego that notify when the app goes into the background or comes to the foreground

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
   and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```
2. in terminal, enter the following command for add lego to project.
```bash
lego add flutter_fgbg_lego
```

## Usage
You can always listen to the app's state changes through the following code.
```dart
EasyEventBus.on('App is in foreground', (event) {
  // write your code here when the app is in the foreground.
});

EasyEventBus.on('App is in background', (event) {
  // write your code here when the app is in the background.
});
```
