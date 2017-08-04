# Vanilla DOM Manipulation
A little "how to" guide with suport to IE9



## Add class
Better support than classList
```
object.getElementById('yourId').className += " yourClassAfterASpace"
``` 

## Remove class
Better support than classList
```
object.getElementById('yourId').className.replace(/\bYourClass\b/,'')
``` 
