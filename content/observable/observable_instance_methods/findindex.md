## [`Rx.Observable.prototype.findIndex(predicate, [thisArg])`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/findindex.js)

{% if book.isPdf %}

![findIndex](http://reactivex.io/documentation/operators/images/findIndex.png)

{% else %}

<rx-marbles key="findIndex"></rx-marbles>

{% endif %}

Searches for an element that matches the conditions defined by the specified predicate, and returns the first occurrence within the entire Observable sequence.
 
#### Arguments
1. `predicate` *(`Function`)*: A function to test each source element for a condition;  The callback is called with the following information:
    1. the value of the element
    2. the index of the element
    3. the Observable object being subscribed
2. `[thisArg]` *(`Any`)*: Object to use as `this` when executing the predicate.

#### Returns
*(`Observable`)*: An Observable sequence with the first element that matches the conditions defined by the specified predicate, if found; otherwise, undefined.

#### Example

[](http://jsbin.com/nodec/1/embed?js,console)

{% if book.isPdf %}



{% else %}

#### Location

- [`rx`](https://www.npmjs.org/package/rx).aggregates.js

{% endif %}