# addClass

Adds the specified class\(es\) to each element in the set of matched elements.

Accepts space-separated `className` for adding multiple classes.

## Parameters

1. classes : `string` / `array` / `function`

## Examples

```javascript
// Passing As String
domQ( "p" ).addClass( "myClass yourClass" );

// Passing As Array
domQ( "p" ).addClass( [ "selected", "highlight" ] )

// Passing As Function
domQ( "ul li" ).addClass(function( index ) {
  return "item-" + index;
});
```

## Quick Links

#### jQuery Documentation : [https://api.jquery.com/addClass/\#addClass-className](https://api.jquery.com/addClass/#addClass-className)

#### Github Soruce : [https://github.com/varunsridharan/domq/blob/main/src/attributes/addClass.js](https://github.com/varunsridharan/domq/blob/main/src/attributes/addClass.js)

