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
| [addClass \(\)](collection-methods/attributes/addclass.md) | add \(\) | css \(\) | data \(\) | height \(\) | hide \(\) |
| attr \(\) | each \(\) |  |  | innerHeight \(\) | show \(\) |
| hasClass \(\) | eq \(\) |  |  | innerWidth \(\) | toggle \(\) |
| prop \(\) | filter \(\) |  |  | outerHeight \(\) |  |
| removeAttr \(\) | first \(\) |  |  | outerWidth \(\) |  |
| removeClass \(\) | get \(\) |  |  | width \(\) |  |
| removeProp \(\) | index \(\) |  |  |  |  |
| toggleClass \(\) | last \(\) |  |  |  |  |
|  | map \(\) |  |  |  |  |
|  | slice \(\) |  |  |  |  |

| Events | Forms | Manipulation | Offset | Traversal |
| :---: | :---: | :---: | :---: | :---: |
| off \(\) | serialize \(\) | after \(\) | offset \(\) | children \(\) |
| on \(\) | val \(\) | append \(\) | offsetParent \(\) | closest \(\) |
| one \(\) |  | appendTo \(\) | position \(\) | contents \(\) |
| ready \(\) |  | before \(\) |  | find \(\) |
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
| isArray \(\) | guid |
| isFunction \(\) | each \(\) |
| isNumeric \(\) | extend \(\) |
| isPlainObject \(\) | parseHTML \(\) |
| isWindow \(\) | unique \(\) |

