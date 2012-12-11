async.once.js
=============

Run a function once and only once. For [async](https://github.com/caolan/async).

Example
-------
```javascript
async = asynconce(async);

var fu = async.once(function() {
    console.log('.once');
});

fu(); //will run
fu(); //will not run
```

You can actually use this in any library (like [jQuery](http://jquery.com/))
```
$ = asynconce($);
```