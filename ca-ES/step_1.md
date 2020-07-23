Sometimes you might have a string which would be more useful to you as an array. For example:

```javascript
var data = "butter sugar eggs flour";
```

The string `data` contains some information separated by spaces. To split the string wherever there is a space and put the results into an array called `ingredients`, you can do this:

```javascript
var data = "butter sugar eggs flour";
var ingredients = data.split(" ");
```

See how this code works and try it out yourself here: <iframe src="https://trinket.io/embed/html/3e59e1063a" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
