gaitonde-1
==========

#CMC Coding Guidelines

## Javascript language rules
### Always use semicolons

### Always use var


### Ok to use nested functions

### Don't use eval()

### Don't use with()

### For loops
Don't use
```
function printArray(arr) {
  for (var key in arr) {
    print(arr[key]);
  }
}
```

Use 
```
function printArray(arr) {
  var length = arr.length;
  for (var i = 0; i < length; i++) {
    print(arr[i]);
  }
}
```

### Use Array and Object literals instead of Array and Object constructors.


## Javascript Style Rules

### In general, use functionNamesLikeThis, variableNamesLikeThis, ClassNamesLikeThis, EnumNamesLikeThis, methodNamesLikeThis, foo.namespaceNamesLikeThis.bar, and filenames-like-this.js.

### Always use namespaces for global code

## Code Formatting
### Spacing
2 space indentation

### Blank lines
Use newlines to group logically related pieces of code. For example:


```
doSomethingTo(x);
doSomethingElseTo(x);
andThen(x);

nowDoSomethingWith(y);

andNowWith(z);
```

### Curly Braces
Because of implicit semicolon insertion, always start your curly braces on the same line as whatever they're opening. For example:

```
if (something) {
  // ...
} else {
  // ...
}
```

### Strings
For consistency single-quotes (') are preferred to double-quotes ("). This is helpful when creating strings that include HTML:

```
var msg = 'This is some HTML';
```
