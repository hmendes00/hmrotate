HMRotate
==========

Rotate html objects using jquery

how to use:

//HTML

```html
<div id="myDiv"></div>
```


//JAVASCRIPT
```html
$("#myDiv").hmRotate();
```
//CSS
```html
.hmrotate-api-rotate-symbol{
    background-image: url('http://www.draw4free.com/help/icons/rotate.png'); //add your custom image here
}
```

P.S: You can also call it with options.. 
e.g:

```html
$("#myDiv").hmRotate({align:'left'}); //also can be right and center

$("myDiv").hmRotate({updatableposition:true}); //default false. This can be used when the object #myDiv also uses draggable jquery.
```

Sample Online:

http://jsfiddle.net/8FmRd/873/
