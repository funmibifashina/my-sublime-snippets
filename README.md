my-sublime-snippets
===================

These are the code snippets I use in Sublime Text 2.

Installation
------------
Save the snippet files in **Packages/User**. You can locate your Packages directory through the main menu: **Preferences > Browse Packages**

Usage
-----
Snippets save you from tedious typing. To use a snippet, type the **Trigger** text, followed by **Tab** to insert the snippet. Continue hitting **Tab** to cycle through all the available fields.


The Snippets
------------
Here is a list of all the available **Triggers**. The underscores in the snippet represent fields.

### JavaScript

#### cons
```javascript
console.log(__);
```

#### log
```javascript
console.log(__);
```

### jQuery

#### &#35;
```javascript
$("#__").
```

#### .
```javascript
$(".__").
```

#### after 
```javascript
$("#__").after("__");
```

#### append 
```javascript
append("__");
```

#### click 
```javascript
$.click(function() {
  __
})
```

#### doc 
```javascript
$(document).ready(function(){
  __
})
```

#### getj 
```javascript
$.getJSON("__", function(__){
  __
});
```

#### each 
```javascript
$.each(__, function(__, __) {
  __
})
```

#### parse 
```javascript
$.parseJSON(${1:variable});)
```

#### post 
```javascript
$.post("__", function(__, __){
__
});
```

#### submit 
```javascript
$.submit(function(){
__
});
```
