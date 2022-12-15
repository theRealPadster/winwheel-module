# winwheel-module
Create spinning prize wheels on HTML canvas with winwheel-module, a fork of Winwheel.js

## Description
winwheel-module is a feature packed JavaScript library that allows you to easily create HTML5 canvas Winning / Prize Wheels, Pie graphs and other things using a highly configurable JavaScript class.

Wheels can be animated using gsap's TweenMax, which contain easing functions and many other powerful animation features.

winwheel-module Features Include:
* Easy to use, highly configurable JavaScript classes.
* Draw wheels using code generated segments or graphically rich images.
* Responsive features so wheels display correctly on different sized devices.
* Numerous text orientation, direction, size and colour options.
* Random or Pre-calculated prize stopping location.
* Play sounds while the wheel is spinning including a "tick" sound.
* Ability to get the segment the user clicked upon.
* Fully commented source code. Plenty of tutorials and other documentation.
* winwheel-module is free to use with an open source license.

## Example
```js
const { Winwheel } = require('./winwheel-module');

let theWheel = new Winwheel({
    'numSegments': 4,
    'segments':
    [
        {'fillStyle': '#eae56f', 'text': 'Prize One'},
        {'fillStyle': '#89f26e', 'text': 'Prize Two'},
        {'fillStyle': '#7de6ef', 'text': 'Prize Three'},
        {'fillStyle': '#e7706f', 'text': 'Prize Four'},
    ],
    'animation':
    {
        'type': 'spinToStop',
        'duration': 5,
        'spins': 8,
    },
});
```

## More examples
To see more examples, please visit the examples section on the original winwheel website http://dougtesting.net/winwheel/examples

## Tutorials and other documentation
Please visit http://dougtesting.net/winwheel/docs to see a complete set of tutorials on how to use winwheel-module as well as other documentation such as class references.

## Original Author
Douglas McKechie https://github.com/zarocknz
## Maintainer
@theRealPadster https://github.com/theRealPadster

## Please note
This wasn't created by me; It is just a fork of Winwheel.js that supports javascript commonjs modules
