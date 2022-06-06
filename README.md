# RxValue React

Adds a single abstract class, `RxComponent`. This component extends from React's Component class,
adding seamless integration with the [rx-value library](https://www.npmjs.com/package/rx-value).

Extend from RxComponent and implement the `configureState` method to return an RxValue.
The component will automatically subscribe to the RxValue when mounting and unsubscribe when unmounting.
No additional call to `setState()` is necessary.
