# slider_confirm_button

Animated slider confirm button that customize color, font , child widgets and more.

## Demo

![Sample Demo](https://github.com/ashanftw/slider_confirm_button/raw/master/untitled.gif)

## How to use

In your pubspec.yaml, include the package
```
dependencies:
  flutter:
    sdk: flutter

  slider_confirm_button: ^0.0.1+6
```

In your code, add import
```
import 'package:slider_confirm_button/slider_confirm_button.dart';
```

Then add the widget to your screen
```
        ConfirmButton(
          width: width,
          height: 55,
          btnOneClickReverseSlider: false,
          btnTwoClickReverseSlider: true,
          btnOneOnpressed: () {
            print('Button one clicked');
          },
          btnTwoOnpressed: () {
            print('Button two clicked');
          },
          mainColor: Color(0XFFb063c5),
          mainChild: new Row(
            children: <Widget>[
              new Text(
                'I accept the Terms of Service',
                overflow: TextOverflow.ellipsis,
              ),
            ],
          ),
          subOneColor: Color(0XFF46b3e6),
          subOneChild: new Row(
            children: <Widget>[
              new Icon(Icons.check_circle_outline),
              new Text(' Confirm')
            ],
          ),
          subTwoColor: Color(0XFFe25822),
          subTwoChild: new Row(
            children: <Widget>[new Icon(Icons.close), new Text(' No')],
          )
        ),
```

Sample code: https://github.com/ashanftw/slider_confirm_button