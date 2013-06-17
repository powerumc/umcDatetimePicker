## Project Description

jQuery DateTimePicker Plugin is able to Choice the time on select options.

## Release History.

- 2012/02/07 Just support option of select tag.
- 2013/06/17 Move to github from codeplex.

## Screenshot the umcDateTimePicker plugin.

![umcDateTimePicker](http://cfile30.uf.tistory.com/image/1476893F4F37A43D2B3866)

## Example

** Script Initialization **
```js
<link type="text/css" href="css/jquery.ui.theme.css" rel="stylesheet" />
<link type="text/css" href="css/jquery.ui.datepicker.css" rel="stylesheet" />
<link type="text/css" href="css/demos.css" rel="stylesheet" />

<script type="text/javascript" src="js/jquery-1.7.1.js"></script>
<script type="text/javascript" src="js/jquery.ui.core.js"></script>
<script type="text/javascript" src="js/jquery.ui.widget.js"></script>
<script type="text/javascript" src="js/jquery.ui.datepicker.js"></script>

<script type="text/javascript" src="src/umcDateTimePicker.js"></script>
```

** Script Loading **
```js
<script type="text/javascript">

$(function () {
    $("#datetimepicker").datetimepicker();
});

</script>
```

** HTML Block **
```js
<input id="datetimepicker" type="text" />
```
