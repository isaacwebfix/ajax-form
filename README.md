
# AJAX Form

Example of a form processed with AJAX using [jQuery](http://jquery.com/), [BackboneJS](http://backbonejs.org/) and a [mediator module](http://addyosmani.com/largescalejavascript/#mediatorpattern) to publish events.
It supports uploading files using the [FormData interface](https://developer.mozilla.org/en-US/docs/Web/API/FormData).

## Browser support
This should work in all modern browsers that support [FormData](http://caniuse.com/#search=XMLHttpRequest%202).

For browsers that don't support FormData, they will submit textual data only.
