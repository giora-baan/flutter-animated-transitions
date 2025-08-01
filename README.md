# Animated Transitions

A Flutter package providing a collection of beautiful and smooth transitions for page navigation. Easily implement complex animations with minimal code.

## Features

- A curated set of high-quality page transitions.
- Simple, controller-based animation management.
- Customizable transition duration and behavior.
- Works with the standard Flutter Navigator.

## Installation

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  animated_transitions: ^0.0.1
```

Then, run `flutter pub get` in your terminal.

## Usage

To use the page transitions, you can wrap your page route with the `TransitionPageRoute` and provide a transition type.

```dart
import 'package:flutter/material.dart';
import 'package:animated_transitions/animated_transitions.dart';

// ...

Navigator.of(context).push(
  TransitionPageRoute(
    page: ScreenB(),
    transition: TransitionType.fadingCircles,
  ),
);
```

For more advanced usage and a full list of available transitions, please see the example application in the `/example` directory.
