# Getting Started

## domQ\(\);

This is the main selector method for domQ. It returns an actionable collection of nodes.

If a function is provided, the function will be run once the DOM is ready.

```javascript
domQ( selector [, element] ) // => collection, using `element` as the context
domQ( selector [, collection] ) // => collection, using `collection` as the context
domQ(node) // => collection
domQ(nodeList) // => collection
domQ(htmlString) // => collection
domQ(collection) // => self
domQ(function () {}) // => document ready callback
```

## Collection Methods

 These methods from the collection prototype \(domQ.fn\) are available once you create a collection with `domQ()` and are called like so:

```javascript
domQ( element ).addClass ( className ) // => collection
```

| Attributes | Collection | CSS | Data | Dimensions | Effects |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [addClass \(\)](collection-methods/attributes/addclass.md) | add \(\) | css \(\) | data \(\) | height \(\) | animate \(\) |
| attr \(\) | each \(\) |  |  | innerHeight \(\) | hide \(\) |
| hasClass \(\) | eq \(\) |  |  | innerWidth \(\) | show \(\) |
| prop \(\) | filter \(\) |  |  | outerHeight \(\) | toggle \(\) |
| removeAttr \(\) | first \(\) |  |  | outerWidth \(\) | fadeIn \(\) |
| removeClass \(\) | get \(\) |  |  | width \(\) | fadeOut \(\) |
| removeProp \(\) | index \(\) |  |  |  | fadeToggle \(\) |
| toggleClass \(\) | last \(\) |  |  |  | fadeTo \(\) |
| copyAttr \(\) | map \(\) |  |  |  | highlight \(\) |
| hasAttr \(\) | slice \(\) |  |  |  | move \(\) |
| moveAttr \(\) | even \(\) |  |  |  | pulse \(\) |
|  | odd \(\) |  |  |  | scale \(\) |

| Events | Forms | Manipulation | Offset | Traversal |
| :---: | :---: | :---: | :---: | :---: |
| off \(\) | val  \(\) | after \(\) | offset \(\) | children \(\) |
| on \(\) | serialize \(\) | append \(\) | offsetParent \(\) | closest \(\) |
| one \(\) | serializeArray \(\) | appendTo \(\) | position \(\) | contents \(\) |
| ready \(\) | serializeObject \(\) | before \(\) |  | find \(\) |
| trigger \(\) |  | clone \(\) |  | has \(\) |
|  |  | detach \(\) |  | is \(\) |
|  |  | empty \(\) |  | next \(\) |
|  |  | html \(\) |  | nextAll \(\) |
|  |  | insertAfter \(\) |  | nextUntil \(\) |
|  |  | insertBefore \(\) |  | not \(\) |
|  |  | prepend \(\) |  | parent \(\) |
|  |  | prependTo \(\) |  | parents \(\) |
|  |  | remove \(\) |  | parentsUntil \(\) |
|  |  | replaceAll \(\) |  | prev \(\) |
|  |  | replaceWith \(\) |  | prevAll \(\) |
|  |  | text \(\) |  | prevUntil \(\) |
|  |  | unwrap \(\) |  | siblings \(\) |
|  |  | wrap \(\) |  |  |
|  |  | wrapAll \(\) |  |  |
|  |  | wrapInner \(\) |  |  |

## Library Methods

| Type Checking | Utilities |
| :---: | :---: |
| isBoolean \(\) | camelCase \(\) |
| isDocument \(\) | attempt \(\) |
| isElement \(\) | parseHTML \(\) |
| isFunction \(\) | pluck \(\) |
| isNodetype \(\) | merge \(\) |
| isNull \(\) | unique \(\) |
| isNumber \(\) | plainObject \(\) |
| isNumeric \(\) | each \(\) |
| isPlainObject \(\) | extend \(\) |
| isString \(\) |  |
| isType \(\) |  |
| isUndefined \(\) |  |
| isWindow \(\) |  |
| isdomQ \(\) |  |
|  |  |

