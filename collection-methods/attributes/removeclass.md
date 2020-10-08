# removeClass

Removes className from collection elements.

Accepts space-separated className for adding multiple classes.

Providing no Parameters will remove all classes.


## Parameters

1. classes : `string` / `array` / `function`


## Examples
### Class List String With Multiple Class

```javascript
domQ( "p" ).removeClass( "myClass yourClass" );
```

### Class List As Array

```javascript
domQ( "p" ).removeClass( [ "myClass", "yourClass" ] );
```

### Function Parameter

```javascript
domQ( "p" ).removeClass( function( elementIndex, element ){
    if( elementIndex > 2 && domQ( element ).attr( 'id' ) === 'myelement' ){
        return 'class-to-remove'; // You Can Also Return A Array of class to remove;
    } 
} );
```


## Quick Links

{% embed url="https://api.jquery.com/removeClass/" caption="jQuery Documentation" %}

{% embed url="https://github.com/varunsridharan/domq/blob/main/src/attributes/removeClass.js" caption="Source File" %}



