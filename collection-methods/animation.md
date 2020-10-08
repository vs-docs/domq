# Animation

Perform a custom animation of a set of CSS properties.

{% hint style="info" %}
domQ uses [Web Animations](https://github.com/web-animations/web-animations-js) which is the latest javascript API for Animations
{% endhint %}

## Parameters

1. keyframes : `object` / `array`
2. speed : `string` / `number`
3. easing : `string`
4. callback : `function`

### Animation Settings

any animation related settings Parameters can be passed with inside keyframes

#### Example

```javascript
domQ( 'p' ).animate({
    direction: "reverse"
    iterations: "2"
});
```

please refer [MDN reference](https://developer.mozilla.org/en-US/docs/Web/API/Element/animate) for detailed info on animation settings Parameters

{% embed url="https://developer.mozilla.org/en-US/docs/Web/API/Element/animate" caption="" %}

### Easing

by default animation api runs with browser supported easing which are

1. `linear`
2. `ease`
3. `ease-in`
4. `ease-out`
5. `ease-in-out`

You can also pass custom easing value like `cubic-bezier(0.42, 0, 0.58, 1)`

Please check for custom easing functions

{% embed url="https://easings.net/" caption="" %}

## Example

```javascript
domQ( 'p' ).animate( {
   opacity: [ 0.5, 1 ],
   transform: [ 'scale(0.5)', 'scale(1)' ],
   direction: 'alternate', // Setting
   duration: 500, // Setting : Supported Values [ 'slow', 'fast' ,'default' ]
   iterations: 20, // Setting
}, function( element ) {
   alert( 'Element Animation is finished' );

   // element variable is actual element object. 
   // you can do what ever you want to do with it.
   domQ( element ).hide(); 
} );
```

## Quick Links

{% embed url="https://github.com/varunsridharan/domq/blob/main/src/animation/animate.js" caption="Source File" %}

