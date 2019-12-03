# Avatar Glow [![GitHub stars](https://img.shields.io/github/stars/apgapg/avatar_glow.svg?style=social)](https://github.com/apgapg/avatar_glow) [![Twitter Follow](https://img.shields.io/twitter/url/https/@ayushpgupta.svg?style=social)](https://twitter.com/ayushpgupta) ![GitHub last commit](https://img.shields.io/github/last-commit/apgapg/avatar_glow.svg) [![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://play.google.com/store/apps/details?id=com.coddu.flutterprofile)[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/apgapg/avatar_glow)


This Flutter package provides a Avatar Glow Widget with cool background glowing animation.

Live Demo: [https://apgapg.github.io/avatar_glow/](https://apgapg.github.io/avatar_glow/)

# 💻 Installation
In the `dependencies:` section of your `pubspec.yaml`, add the following line:

[![Version](https://img.shields.io/pub/v/avatar_glow.svg)](https://pub.dartlang.org/packages/avatar_glow)

```yaml
dependencies:
  avatar_glow: <latest version>
```

# ❔ Usage

### Import this class

```dart
import 'package:avatar_glow/avatar_glow.dart';
```

#### Usage is simple. Avatar Glow is a widget offering different customizable optional parameters with child displayed at its center.

<img src="https://raw.githubusercontent.com/apgapg/avatar_glow/master/src/app.gif"  height = "400" alt="PieChart">


### - Simple Implementation
```dart
AvatarGlow(
    endRadius: 90.0,   //required
    child: Material(   //required
      elevation: 8.0,
      shape: CircleBorder(),
      child: CircleAvatar(
        backgroundColor:Colors.grey[100] ,
        child: Image.asset('assets/images/flutter.png',height: 60,),
        radius: 40.0,
        shape: BoxShape.circle
      ),
    ),
  )
```

### - Full Implementation
```dart
AvatarGlow(
    startDelay: Duration(milliseconds: 1000),
    glowColor: Colors.blue,
    endRadius: 90.0,
    duration: Duration(milliseconds: 2000),
    repeat: true,
    showTwoGlows: true,
    repeatPauseDuration: Duration(milliseconds: 100),
    child: Material(
      elevation: 8.0,
      shape: CircleBorder(),
      child: CircleAvatar(
        backgroundColor:Colors.grey[100] ,
        child: Image.asset('assets/images/flutter.png',height: 60,),
        radius: 40.0,
        shape: BoxShape.circle
      ),
    ),
    shape: BoxShape.circle,
    animate: true,
    curve: Curves.fastOutSlowIn,
  )
```
# ⭐ My Flutter Packages
- [json_table](https://pub.dartlang.org/packages/json_table)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/json_table.svg?style=social)](https://github.com/apgapg/json_table)  Create Flutter Json Table from json map directly.
- [pie_chart](https://pub.dartlang.org/packages/pie_chart)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/pie_chart.svg?style=social)](https://github.com/apgapg/pie_chart)  Flutter Pie Chart with cool animation.
- [search_widget](https://pub.dartlang.org/packages/search_widget)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/search_widget.svg?style=social)](https://github.com/apgapg/search_widget)  Flutter Search Widget for selecting an option from list.
- [animating_location_pin](https://pub.dev/packages/animating_location_pin)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/animating_location_pin.svg?style=social)](https://github.com/apgapg/animating_location_pin)  Flutter Animating Location Pin Widget providing Animating Location Pin Widget which can be used while fetching device location.

# ⭐ My Flutter Apps
- [flutter_profile](https://github.com/apgapg/flutter_profile)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/flutter_profile.svg?style=social)](https://github.com/apgapg/flutter_profile)  Showcase My Portfolio: Ayush P Gupta on Playstore.
- [flutter_sankalan](https://github.com/apgapg/flutter_sankalan)  [![GitHub stars](https://img.shields.io/github/stars/apgapg/flutter_sankalan.svg?style=social)](https://github.com/apgapg/flutter_sankalan)  Flutter App which allows reading/uploading short stories.

# 👍 Contribution
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
