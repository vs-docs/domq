# toggleClass

Adds or removes className from collection elements based on if the element already has the class.

Accepts space-separated classNames for toggling multiple classes, and an optional force boolean to ensure classes are added \( `true` \) or removed \( `false` \).

## Parameters

1. className : `string` / `array` / `function`
2. state : `boolean`

## Example

### Class Names As String

```javascript
domQ( "div.foo" ).toggleClass( 'highlight' );
```

### Class Names As Array

```javascript
domQ( "div.foo" ).toggleClass( [ 'highlight','border-red' ] );
```

### Function Callback

```javascript
domQ( "div.foo" ).toggleClass(function() {
  if ( domQ( this ).parent().is( ".bar" ) ) {
    return "happy";
  } else {
    return "sad";
  }
});
```

## Quick Links

{% embed url="https://api.jquery.com/toggleClass/" caption="jQuery Documentation" %}

{% embed url="https://github.com/varunsridharan/domq/blob/main/src/attributes/toggleClass.js" caption="Source File" %}

