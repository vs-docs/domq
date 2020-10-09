# hasClass

Returns the boolean result of checking if any element in the collection has the `className` attribute.

## Parameters

1. classes : `string` The class name to search for

## Returns

`true` if class exists or it will return `false`

## Examples

```javascript
// returns true if class exists or will return false;
if( domQ( "p" ).hasClass( "myClass yourClass" ) ){
    // your code here
}
```

## Quick Links

{% embed url="https://api.jquery.com/hasClass/" caption="jQuery Documentation" %}

{% embed url="https://github.com/domq-js/core/blob/main/src/attributes/hasClass.js" caption="Source File" %}



