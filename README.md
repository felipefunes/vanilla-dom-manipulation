# Vanilla DOM Manipulation
A little "how to" guide with suport to IE9


Thanks for the add and remove class to Tom Cafferkey http://www.tjcafferkey.me/
## Add class
Better support than classList
```
function addClass(elem, className){
    if(elem.className.indexOf(className) == -1) {
        elem.className += className;
    }          
}
``` 

## Remove class
Better support than classList
```
function removeClass(elem, name) {
   if (hasClass(elem, name)) {
      elem.className=elem.className.replace(new RegExp('(\\s|^)'+name+'(\\s|$)'),' ').replace(/^\s+|\s+$/g, '');
    }
}
``` 
