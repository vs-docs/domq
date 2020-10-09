---
description: Adds the specified class(es) to each element in the set of matched elements.
---

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

{% embed url="https://api.jquery.com/addClass/" caption="jQuery Documentation" %}

{% embed url="https://github.com/domq-js/core/blob/main/src/attributes/addClass.js" caption="Source File" %}

