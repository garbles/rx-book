## [`Rx.Observable.prototype.doOnError(onError, [thisArg])`, `Rx.Observable.prototype.tapOnError(onError, [thisArg])`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/do.js)

{% if book.isPdf %}

![doOnError](http://reactivex.io/documentation/operators/images/doOnError.png)

{% else %}



{% endif %}

Invokes an action upon exceptional termination of the observable sequence.

This method can be used for debugging, logging, etc. of query behavior by intercepting the message stream to run arbitrary actions for messages on the pipeline.

#### Arguments
1. `onError` *(`Function`)*: Function to invoke upon exceptional termination of the observable sequence.
2. [`thisArg`] *(Any)*: Object to use as this when executing callback.

#### Returns
*(`Observable`)*: The source sequence with the side-effecting behavior applied.

#### Example

##### Using a function

[](http://jsbin.com/girara/1/embed?js,console)

##### Using a thisArg

[](http://jsbin.com/keqovo/1/embed?js,console)

{% if book.isPdf %}



{% else %}

### Location

File:
- [`/src/core/linq/observable/do.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/do.js)

Dist:
- [`rx.all.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.all.js)
- [`rx.all.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.all.compat.js)
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-All`](http://www.nuget.org/packages/RxJS-All/)
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/do.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/do.js)

{% endif %}
