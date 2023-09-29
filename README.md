## Please use [Counter-Up](https://github.com/ashrafuzzaman04/Counter-Up) instead, Counter Up 2 greatly improves on Counter Up, has no dependencies, lightweight, uses modern code, and more.

# Counter-Up

Counter-Up is a jQuery plugin that _animates_ a number from zero (counting up towards it). It supports counting up:

- integers `12345`
- floats `0.1234`
- formatted numbers `1,234,567.00`

Features:

- Auto-detect for integers, floats or formatted numbers
- The plugin will also use the number of decimal places the original number is using.
- Lightweight: ~1kb
- Minimal setup

_Requires [waypoints.js](http://imakewebthings.com/jquery-waypoints/)_

# Demo

**[DEMO](http://bfintal.github.io/Counter-Up/demo/demo.html)**

# Usage

**Include**

```
<script src="http://cdnjs.cloudflare.com/ajax/libs/waypoints/2.0.3/waypoints.min.js"></script>
<script src="jquery.counterup.min.js"></script>
```

**HTML**

```
<span class="counter">1,234,567.00</span>
<span>$</span><span class="counter">1.99</span>
<span class="counter">12345</span>
```

**jQuery**

```
$('.counter').counterUp();
```

**or with extra parameters**

```
$('.counter').counterUp({
    delay: 10,
    time: 1000
});
```

`delay` - The delay in milliseconds per number count up

`time` - The total duration of the count up animation

# Social Stuff

Linkedin: [@bfintal](https://www.linkedin.com/in/ashraf-uzzaman/)

Facebook: <a href='https://www.facebook.com/ashraf.uzmahim/' rel='author'>Ashraf Uzzaman</a>
