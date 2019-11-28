<<<<<<< HEAD
<img src="https://github.com/ashanftw/slider_confirm_button/raw/master/untitled.gif" alt="Demo Image" style="max-width:50%;">
=======
<img src="https://github.com/ashanftw/slider_confirm_button/raw/master/untitled.gif" alt="Sample Demo" style="width:450px;">
>>>>>>> 0e62adff6f40b6ed64f37e48aa061001458f7b00
<pre>
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
)),
</pre>
