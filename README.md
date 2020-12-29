# Flutter Gradients

<img src="https://raw.githubusercontent.com/JonathanMonga/flutter_gradients/master/images/header.jpg" alt="Header" height="40%" width="90%"/>

A curated collection of splendid gradients made in Dart (port of [https://webgradients.com](https://webgradients.com) for Flutter). Only linear gradients included for now.

[![Pub](https://img.shields.io/badge/pub-0.0.1-blue)](https://pub.dev/packages/flutter_gradients)
[![Build Status](https://travis-ci.org/JonathanMonga/flutter_gradients.svg?branch=master)](https://travis-ci.org/JonathanMonga/flutter_gradients)

## Installation

Add the Package

```yaml
dependencies:
  flutter_gradients: ^0.0.1
```

# ❔ Usage

### Import the package

```dart
import 'package:flutter_gradients/flutter_gradients.dart';
```

## How To Use

See how easy it is to get a LinearGradient

<img src="https://raw.githubusercontent.com/JonathanMonga/flutter_gradients/master/images/war_flame.png" align = "right" height = "350" alt="Exemple">

```dart
    Container(
        width: 150,
        height: 150,
        decoration: BoxDecoration(
            shape: BoxShape.circle,
            [gradient: FlutterGradient.warmFlame()],
        ),
    );
```

## Catalogue

| <img src="https://raw.githubusercontent.com/JonathanMonga/flutter_gradients/master/images/image_01.png" height = "350" alt="Image 01"> | <img src="https://raw.githubusercontent.com/JonathanMonga/flutter_gradients/master/images/image_02.png" height = "350" alt="Image 02">

## Examples

Web and command-line examples can be found in the `example` folder.

### Web Examples

In order to run the web examples, please follow these steps:

1. Clone this repo and enter the directory
2. Run `pub get`
3. Run `pub run build_runner serve example`
4. Navigate to [http://localhost:8080/web/](http://localhost:8080/web/) in your browser

### Command Line Examples

In order to run the command line example, please follow these steps:

1. Clone this repo and enter the directory
2. Run `pub get`
3. Run `dart example/lib/main.dart`

### Flutter Example

#### Install Flutter

In order to run the flutter example, you must have Flutter installed. For installation instructions, view the online
[documentation](https://flutter.io/).

#### Run the app

1. Open up an Android Emulator, the iOS Simulator, or connect an appropriate mobile device for debugging.
2. Open up a terminal
3. `cd` into the `example/lib/` directory
4. Run `flutter doctor` to ensure you have all Flutter dependencies working.
5. Run `flutter packages get`
6. Run `flutter run`

# License

    MIT License

    Copyright (c) 2020 Jonathan Monga

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
