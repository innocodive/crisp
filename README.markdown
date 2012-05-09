##crisp.js

Build css3 buttons with a single line of javascript. [Demo](http://bouchon.github.com/crisp).

##Usage
A button is just a regular element. To change its look or feel more than the in the example above, just create it and style it like you would any other element. Same goes for registering event handlers and positioning.

* Build a fricken button

```javascript
var button = crisp.create({innerHTML: 'click me'});
```

* Build a fricken button and place it in the DOM

```javascript
var button = crisp.create({innerHTML: 'click me'});
document.getElementById('foo').appendChild(button);
```

* Build a fricken button using all config options

```javascript
var args = {
  innerHTML: 'gordon',   // button text
  width: '100px',        // button width
  height: '40px',        // button height
  color: '#FF0022',      // text color
  bgColor: 'green',      // background color
  fontFamily: 'Arial',   // font face
  fontSize: '20px'       // font size
}
var button = crisp.create(args);
document.getElementById('foo').appendChild(button);
```

##Issues & Features

File under the Issues section or feel free to fork and pull-request

##License

WTFPL