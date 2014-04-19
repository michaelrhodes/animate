# animate
animate is a small wrapper around requestAnimationFrame that adds a frame rate constraint. It also provides simple `pause` and `resume` methods.

[![Browser support](https://ci.testling.com/michaelrhodes/animate.png)](https://ci.testling.com/michaelrhodes/animate)

## Install
```sh
$ npm install animate
```

### Example
``` js
var animate = require('animate')

// Run the frame 24 times a second.
var animation = animate(function frame() {
  // Blah, blah, some animation.
}, 24)

animation.pause()
animation.resume()
```

### License
[MIT](http://opensource.org/licenses/MIT)
