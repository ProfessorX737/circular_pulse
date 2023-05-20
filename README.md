# Circular Pulse [![GitHub stars](https://img.shields.io/github/stars/ProfessorX737/circular_pulse.svg?style=social)](https://github.com/ProfessorX737/circular_pulse) [![Twitter Follow](https://img.shields.io/twitter/url/https/@ayushpgupta.svg?style=social)](https://twitter.com/ayushpgupta) ![GitHub last commit](https://img.shields.io/github/last-commit/ProfessorX737/circular_pulse.svg) [![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://play.google.com/store/apps/details?id=com.coddu.flutterprofile)[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ProfessorX737/circular_pulse)

This Flutter package provides a Circular Pulse Widget with cool background glowing animation. Forked from https://pub.dev/packages/avatar_glow put re-published for control/stability

# 💻 Installation
In the `dependencies:` section of your `pubspec.yaml`, add the following line:

[![Version](https://img.shields.io/pub/v/circular_pulse.svg)](https://pub.dartlang.org/packages/circular_pulse)

```yaml
dependencies:
  circular_pulse: <latest version>
```

To use the latest changes:

```yaml
  circular_pulse:
    git:
      url: https://github.com/ProfessorX737/circular_pulse
      ref: master
```

# ❔ Usage

### Import this class

```dart
import 'package:circular_pulse/circular_pulse.dart';
```

Usage is simple. Circular Pulse is a widget offering different customizable optional parameters with child displayed at its center.

### - Simple Implementation
```dart
CircularPulse(
 endRadius: 60.0,
 child: Material(     // Replace this child with your own
   elevation: 8.0,
   shape: CircleBorder(),
   child: CircleAvatar(
     backgroundColor: Colors.grey[100],
     child: Image.asset(
       'assets/images/dart.png',
       height: 50,
     ),
     radius: 30.0,
   ),
 ),
),
```

### - Full Implementation
```dart
CircularPulse(
 glowColor: Colors.blue,
 endRadius: 90.0,
 duration: Duration(milliseconds: 2000),
 repeat: true,
 showTwoGlows: true,
 repeatPauseDuration: Duration(milliseconds: 100),
 child: Material(     // Replace this child with your own
   elevation: 8.0,
   shape: CircleBorder(),
   child: CircleAvatar(
     backgroundColor: Colors.grey[100],
     child: Image.asset(
       'assets/images/flutter.png',
       height: 60,
     ),
     radius: 40.0,
   ),
 ),
),
```

# 👍 Contribution
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
