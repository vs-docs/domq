# attr

Without attrValue, returns the attribute value of the first element in the collection.

With attrValue, sets the attribute value of each element of the collection.

## Parameters

1. attrName : `string` / `object`
2. attrValue : `string` / `number` / `null`

## Example

### Setting A Single Attribute

```javascript
domQ( "img" ).attr( "alt", "Brush Seller" );
```

### Setting Multiple Attribute

```javascript
domQ( "img" ).attr({
  alt: "Brush Seller",
  title: "photo by Clark"
});
```

### Getting Attribute Value

```javascript
var value = domQ( 'img' ).attr( 'src' );
console.log( value );
```

## Quick Links

{% embed url="https://api.jquery.com/attr/" caption="jQuery Documentation" %}

{% embed url="https://github.com/varunsridharan/domq/blob/main/src/attributes/attr.js" caption="Source File" %}

