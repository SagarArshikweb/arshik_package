
# Fancy Containers

Fancy container package lets you add a beautiful gradient container to your Flutter app.

## Installation

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):
```yaml
dependencies:
  flutter_package: ^0.0.2
```
2. Import the package and use it in your Flutter App.
```dart
import 'package:flutter_package/flutter_package.dart';
```

## Example
There are a number of properties that you can modify:

-  height
- width
- title
- subtitle
- gradient (color1 and color2)

<hr>

<table>
<tr>
<td>

```dart
class FancyScreen extends StatelessWidget {  
  const FancyScreen({Key? key}) : super(key: key);  
  
  @override  
  Widget build(BuildContext context) {  
    return Scaffold(  
      body: Center(  
        child: const FancyContainer(  
          title: 'Hello World',  
          color1: Colors.lightGreenAccent,  
          color2: Colors.lightBlue,  
          subtitle: 'This is a new package',  
        ),  
      ),  
    );  
  }  
}
```

</td>
</tr>
</table>

## Next Goals

- [x] Add onTap for functions.
  Now, you can specify the onTap and specify a function.

- [x] Change font and color style for text.
  Change color by specifying `textcolor` and `subtitlecolor` properties.

- [ ] Add more containers to the package.