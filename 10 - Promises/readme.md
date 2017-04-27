### Promises

Promises are often used when fetching Json APIs (aka AJAX).

The `Promise` object is used for asynchronous computations. A `Promise` represents a value which may be available now, or in the future, or never.

At their most basic, promises are a bit like event listeners except:

* A promise can only succeed or fail once. It cannot succeed or fail twice, neither can it switch from success to failure or vice verse.
* If a promise has succeeded or failed and you later add a success/failur callback, the correct callback will be called, even though the even took place earlier.

This is extremely useful for async success/failure, because you're less interested in the exact time something became available, and more interested in reacting to the outcome.

A `Promise` is in one of these states:

* _pending_: initial state, not fulfilled or rejected.
* _fulfilled_: meaning that the operation completed successfully.
* _rejected_: meaning that the operation failed.

#### Code examples

1. Instantiating a new Promise object
2. Chaining Promises + Flow control (cascading)
3. Working with multiple Promises

#### Further reading:
* "[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)" - Mozilla Developer Network
* "[JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/promises)" - Jake Archibald (Google Developers)
* "[Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)" - Mozilla Developer Network (MDN)
* "[Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)" - Mozilla Developer Network (MDN)
